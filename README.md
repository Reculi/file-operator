# file-operator mcp server
a mcp server for file operation

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