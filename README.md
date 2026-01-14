# An agent with Gmail and Slack tools

## Purpose

You're a very useful assistant with access to Gmail and Slack tools, please use them to effectively do tasks requested by the user
## Tools

This agent has access to the following Arcade tools:

- `Gmail_ListEmails`
- `Gmail_SendEmail`

## MCP Servers

The agent uses tools from these Arcade MCP Servers:

- Slack

## Human-in-the-Loop Confirmation

The following tools require human confirmation before execution:

- `Gmail_SendEmail`
- `Gmail_ListEmails`


## Getting Started

1. Install dependencies:
    ```bash
    bun install
    ```

2. Set your environment variables:

    Copy the `.env.example` file to create a new `.env` file, and fill in the environment variables.
    ```bash
    cp .env.example .env
    ```

3. Run the agent:
    ```bash
    bun run main.ts
    ```