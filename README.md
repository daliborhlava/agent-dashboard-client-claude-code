# Agent Dashboard - Claude Code Client

Claude Code plugin for [agent-dashboard](https://github.com/daliborhlava/agent-dashboard) monitoring server.

Sends real-time events to a central dashboard including:
- Session start/end
- Tool usage (pre/post)
- Conversation transcript
- Permission prompts

## Installation

```bash
# Add the marketplace
/plugin marketplace add daliborhlava/agent-dashboard-client-claude-code

# Install the plugin
/plugin install agent-monitor@agent-dashboard
```

## Configuration

Set the dashboard server URL via environment variable:

```bash
export AGENT_MONITOR_URL="http://your-server:8787"
```

Default: `http://localhost:8787`

Add to your `~/.bashrc` or `~/.zshrc` for persistence.

## Server

The monitoring server is available at [daliborhlava/agent-dashboard](https://github.com/daliborhlava/agent-dashboard).

## Updates

```bash
/plugin marketplace update
```

## License

MIT
