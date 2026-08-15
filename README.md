# Claude Code plugins

Claude Code plugin marketplace for the [delphi-blocks](https://github.com/delphi-blocks) open source projects.

## What's in here

| Plugin | Description |
| --- | --- |
| `mcpconnect` | Build MCP servers in Delphi with [MCPConnect](https://github.com/delphi-blocks/MCPConnect): create a new server (stdio, WebBroker or Indy), add tools, resources, resource templates, App UIs and prompts, and set up sessions, notifications and OAuth security. |

The `mcpconnect` plugin ships the `mcpconnect-dev` skill, which triggers on its own when you work on an MCPConnect project (or ask to expose Delphi code to an LLM). It carries reference files on tools, resources and prompts, sessions and notifications, server setup, and security.

## Installing the marketplace

From inside Claude Code:

```
/plugin marketplace add delphi-blocks/claude-plugins
```

Then install the plugin you need:

```
/plugin install mcpconnect@delphi-blocks
```

Alternatively, `/plugin` opens the interactive menu, where you can browse and install the marketplace plugins.

## Updating

To refresh the list of available plugins and the installed versions:

```
/plugin marketplace update delphi-blocks
```

To remove the marketplace entirely:

```
/plugin marketplace remove delphi-blocks
```

## License

MIT — see [LICENSE](LICENSE).
