# file-operator mcp server
[![smithery badge](https://smithery.ai/badge/@Reculi/file-operator)](https://smithery.ai/server/@Reculi/file-operator)
a mcp server for file operation

### Installing via Smithery

To install file-operator for Claude Desktop automatically via [Smithery](https://smithery.ai/server/@Reculi/file-operator):

```bash
npx -y @smithery/cli install @Reculi/file-operator --client claude
```

# Environment requirement
you have to make sure you installed uv

# Server Configuration
```
{
    "mcpServers": {
        "file-operator": {
            "command": "uv",
            "args": [
                "--directory",
                "PATH\TO\YOUR\WEATHER\MCP\SERVER",
                "run",
                "list_dict.py"
            ]
        }
    }
}
```
