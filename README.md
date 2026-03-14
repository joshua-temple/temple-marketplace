# Claude Marketplace

Claude Code plugin marketplace by Joshua Temple.

## Available Plugins

| Plugin | Description | Version |
|--------|-------------|---------|
| [autopilot](https://github.com/joshua-temple/autopilot) | Autonomous goal-driven task execution with heartbeat safety net | 0.1.0 |

## Installation

Add this marketplace to Claude Code:

```
/install-marketplace https://github.com/joshua-temple/claude-marketplace
```

Then install any plugin:

```
/plugin autopilot
```

## Adding Plugins

To add a new plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json` with the plugin's GitHub URL and metadata.
