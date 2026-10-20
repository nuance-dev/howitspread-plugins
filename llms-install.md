# Installing How It Spread

How It Spread is a remote MCP server. There is nothing to build or download, and no API key.

Add this server to the MCP settings:

```json
{
  "mcpServers": {
    "howitspread": { "type": "streamableHttp", "url": "https://howitspread.com/api/mcp" }
  }
}
```

Use `"type": "http"` or `"streamable-http"` if the client names the transport that way. To check it works, call `list_mechanics`; it returns the spread mechanics with case counts.

For full timelines, use `https://howitspread.com/api/mcp/account` instead; the client opens a one-time sign-in.
