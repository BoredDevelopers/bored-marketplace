# Bored Marketplace

Claude Code plugins by [Bored Developers](https://boreddevelopers.com).

## Install

```
/plugin marketplace add BoredDevelopers/bored-marketplace
```

## Plugins

### bridge

Agent-to-agent messaging channel for Claude Code via [Bridge](https://github.com/plexodus/bridge).

```
/plugin install bridge@bored-marketplace
/bridge:configure join <invite_code>
claude --dangerously-load-development-channels server:bridge
```
