# Apple MCP tools

This is a collection of apple-native tools for the [MCP protocol](https://modelcontextprotocol.com/docs/mcp-protocol).


## Features

- Send and retrieve messages from Apple Messages app
- Search and open notes in Apple Notes app
- Search and open contacts in Apple Contacts app
- TODO: Search and open calendar events in Apple Calendar app
- TODO: Search and open reminders in Apple Reminders app
- TODO: Search and open photos in Apple Photos app
- TODO: Search and open music in Apple Music app

## Installation

You just need to have `npx` installed.

```claude_desktop_config.json
{
  "mcpServers": {
    "apple-mcp": {
      "command": "npx",
      "args": ["@dhravya/apple-mcp@latest"]
    }
  }
}
```

Now, ask Claude to use the `apple-mcp` tool.

```
Can you send a message to John Doe?
```

```
find all the notes related to AI and send it to my girlfriend
```

## Local Development

```bash
git clone https://github.com/dhravya/apple-mcp.git
cd apple-mcp
bun install
bun run index.ts
```

enjoy!
