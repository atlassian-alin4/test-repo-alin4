# Connect Claude Code to Jira

Connect Claude Code to Jira to automate code changes, draft PRs, and progress work automatically.

## Prerequisites

- A Jira Cloud instance with [Rovo](https://www.atlassian.com/software/rovo/guides/admin-guide/rovo-activation#confirm-activation) enabled.
- Admin rights to install a coding app, or a request submitted to your admin.
- An active Claude Code subscription.
- A code repository the agent can work in.

## Credentials

The Claude for Jira coding agent requires two credentials:

- An Anthropic API key for **Claude Managed Agents**
- A **GitHub personal access token** for your GitHub service account

Never commit these credentials to the repository. Enter them only in the Claude Agent for Jira configuration screen.

## Setup

1. Go to the [Claude for Jira](https://marketplace.atlassian.com/apps/com.atlassian.agent.claude.for.jira) app on the Atlassian Marketplace.
2. Select **Get it now**, choose your site, then review and install the app (or submit a request to your admin).
3. Go to **Project settings → Apps → Manage apps**.
4. Find **Claude Agent for Jira** and select **Configure**.
5. In the **Claude Managed Agents API Key** field, paste your API key.
6. Once verified, click **Create Agent** and confirm the Claude agent appears in your Anthropic Console.
7. In the **GitHub Personal Access Token** field, paste and verify your access token.
8. Click **Save configuration**.

For more information, see the [full setup guide](https://support.atlassian.com/jira-software-cloud/docs/set-up-claude-agent-for-jira/).
