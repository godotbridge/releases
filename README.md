# GodotBridge — Downloads

Pre-built MCP server packages for GodotBridge.

## Quick install

### pip (recommended)

```bash
pip install godotbridge
```

### Manual download

Go to [Releases](https://github.com/godotbridge/releases/releases) and download the package for your platform:

| Platform | File |
|----------|------|
| Windows | `godotbridge-1.0.0-win-x64.zip` |
| macOS (Intel) | `godotbridge-1.0.0-macos-x64.tar.gz` |
| macOS (Apple Silicon) | `godotbridge-1.0.0-macos-arm64.tar.gz` |
| Linux | `godotbridge-1.0.0-linux-x64.tar.gz` |

## Setup

1. **Install the Godot addon** — from the [Godot Asset Library](https://godotengine.org/asset-library/asset) (search "GodotBridge") or from [godotbridge/addon](https://github.com/godotbridge/addon)

2. **Install the MCP server** — via pip or manual download (see above)

3. **Register with your AI client:**

   **Claude Code:**
   ```bash
   claude mcp add godot-bridge -- godotbridge
   ```

   **Claude Desktop / Cursor / Windsurf:**
   ```json
   {
     "mcpServers": {
       "godot-bridge": {
         "command": "godotbridge"
       }
     }
   }
   ```

4. **Enable the plugin** in Godot: Project Settings > Plugins > GodotBridge > Enable

5. **Start building** — open a new AI session in your project folder

## Licensing

- **Lite (free)**: 67 tools across 12 categories — no license needed
- **Full ($29)**: All 345 tools across 36 categories — one-time purchase at [godotbridge.com](https://godotbridge.com)

Activate your license:
```bash
# Option A: environment variable (persistent)
set GODOT_MCP_LICENSE_KEY=YOUR-KEY-HERE

# Option B: via MCP tool (session only)
# Ask your AI: "activate_license with key YOUR-KEY-HERE"
```

## Links

- [Website](https://godotbridge.com)
- [Godot Addon](https://github.com/godotbridge/addon)
- [Report Issues](https://github.com/godotbridge/releases/issues)
