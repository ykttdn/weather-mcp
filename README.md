# [Weather MCP Server](https://modelcontextprotocol.io/docs/develop/build-server#node)

We use Node.js via [Volta](https://volta.sh/).
Add below to `/Users/your-name/Library/Application Support/Claude/claude_desktop_config.json`:

```jsonc
{
  "mcpServers": {
    "weather": {
      "command": "/absolute/path/to/.volta/bin/node", // Run `which node`
      "args": ["/absolute/path/to/build/index.js"]
    }
  }
}
```
