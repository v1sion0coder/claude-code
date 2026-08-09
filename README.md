# claude-code

## MCP servers

This repo defines a project-level MCP server in `.mcp.json` for the GitHub
Copilot MCP server (`https://api.githubcopilot.com/mcp`), used by Claude Code
and compatible MCP clients.

Before using it, set a `GITHUB_PAT` environment variable with a GitHub
personal access token:

```sh
export GITHUB_PAT=your_token_here
```

Claude Code will pick up `.mcp.json` automatically when you open this
project and substitute `${GITHUB_PAT}` from your environment.
