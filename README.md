# How It Spread for AI assistants

Viral precedents, cited and dated. One remote MCP server, `https://howitspread.com/api/mcp`, with no sign-in and no key, plus a `viral-precedents` skill that turns a brief into cited cases.

## Install

Claude Code and Cowork:

```
/plugin marketplace add https://howitspread.com/plugin.git
/plugin install howitspread@howitspread
```

Gemini CLI:

```
gemini extensions install https://howitspread.com/plugin.git
```

Anything else that speaks MCP: add `https://howitspread.com/api/mcp` as a remote (Streamable HTTP) server. Every client: https://howitspread.com/mcp

## What it reads

- Anyone: search, Spread Scores, summaries and the first events of every case.
- Free account (`/api/mcp/account`, one sign-in): every case's full, dated timeline.
- Pro: why it worked, what to do, every sourced number and the sources.

Tools: `search_cases`, `get_case`, `list_mechanics`. All read-only.

Support: hello@howitspread.com
