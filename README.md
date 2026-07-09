# HOL DevContainer Features

[DevContainer features](https://containers.dev/features) by [HOL](https://hol.org) for securing AI coding agents in development containers.

## Available Features

| Feature | Description |
|---------|-------------|
| [HOL Guard](src/hol-guard/README.md) | Local-first security for AI coding agents (Codex, Claude Code, Cursor, Gemini, OpenCode, Pi) |

## Usage

Add a feature to your `devcontainer.json`:

```json
{
    "features": {
        "ghcr.io/hashgraph-online/devcontainer-features/hol-guard:1": {}
    }
}
```

Features are automatically published to the GitHub Container Registry via this repo.

## About HOL Guard

[HOL Guard](https://hol.org/guard) intercepts tool actions before files change or networks are contacted, protecting AI coding agents from supply-chain attacks in plugins and MCP servers.

- [Documentation](https://hol.org/guard)
- [GitHub](https://github.com/hashgraph-online/hol-guard)
- [PyPI](https://pypi.org/project/hol-guard/)
