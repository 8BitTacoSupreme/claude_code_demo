# Claude Code Demo with Flox

This repository demonstrates setting up a reproducible development environment using [Flox](https://flox.dev/) with Claude Code integration.

## What's Inside

This project showcases:

- **Flox Environment**: A declarative, reproducible development environment
- **Claude Code**: Anthropic's official CLI tool for Claude (v2.0.30)
- **Flox MCP Server**: Model Context Protocol server for Flox integration (v0.1.1)

## Getting Started

### Prerequisites

- [Flox](https://flox.dev/) installed on your system

### Activating the Environment

To activate this Flox environment and access all installed tools:

```bash
flox activate
```

This will automatically make available:
- `claude-code` - The Claude Code CLI
- Flox MCP server for enhanced integration

## Installed Packages

- **claude-code** (2.0.30) - Interactive CLI tool for Claude AI
- **flox-mcp-server** (0.1.1) - MCP server for Flox package management

## Why Flox?

Flox provides:
- **Reproducibility**: Everyone gets the same development environment
- **Portability**: Works across macOS, Linux, and Windows (WSL)
- **Declarative**: Environment configuration as code
- **Isolation**: No conflicts with system packages

## Learn More

- [Flox Documentation](https://flox.dev/docs)
- [Claude Code Documentation](https://docs.claude.com/en/docs/claude-code)
- [Model Context Protocol](https://modelcontextprotocol.io/)
