# Escape Velocity Claude Plugins

The [Claude plugin marketplace](https://code.claude.com/docs/en/plugins/create-marketplace.md) for plugins by Escape Velocity. This repository holds only the catalog. Each plugin's source lives in its own repository.

## Plugins

| Plugin | Description | Source |
|---|---|---|
| `mission-lock` | Mission Lock Analyzer: analyzes a company's governing documents for how durably its mission is protected. | [escape-velocity-co/mission-lock](https://github.com/escape-velocity-co/mission-lock) |

## Installation

In Claude Code:

```
/plugin marketplace add escape-velocity-co/claude-plugins
/plugin install mission-lock@escape-velocity
```

In the Claude apps, open **Customize → Plugins → Add marketplace** and enter `escape-velocity-co/claude-plugins`.

## License

Copyright © 2026 Escape Velocity. Licensed under the [Mozilla Public License 2.0](LICENSE). Each plugin is licensed separately; see its repository.
