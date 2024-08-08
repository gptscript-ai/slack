# ARCHIVED

This repo has been archived and is no longer maintained. We recommend using the Slack tools available in [gptscript-ai/integrations](https://github.com/gptscript-ai/integrations).

# slack

This is a GPTScript tool for interacting with Slack workspaces. It can search for messages, and list the channels and users in the workspace.

## Setup and Usage

1. Create a new Slack app in your workspace.
2. Give your app the following User Token scopes:
   - `channels:read`
   - `channels:history`
   - `search:read`
   - `users:read`
3. Install the app to your workspace.
4. Get your User OAuth Token from the app's "OAuth & Permissions" page.
5. Set the token to the environment variable `GPTSCRIPT_SLACK_TOKEN`.
6. Now you can use the tool in a script:

```
Tools: github.com/gptscript-ai/slack

Has anyone mentioned Disney in the past month?
```
