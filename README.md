# conduitAI CLI

Search, install, and manage AI tools for Claude Code, Cursor, and Windsurf.

## Install

### macOS (Homebrew)

```bash
brew tap conduit-technologies/tap
brew install conduitai
```

### Windows (Scoop)

```powershell
scoop bucket add conduitai https://github.com/conduit-technologies/scoop-bucket
scoop install conduitai
```

### Windows (winget)

```powershell
winget install ConduitTechnologies.conduitai
```

### Linux

```bash
curl -fsSL https://github.com/conduit-technologies/conduitai-cli/releases/latest/download/conduitai-linux-x64 -o conduitai
chmod +x conduitai
sudo mv conduitai /usr/local/bin/
```

### npm (all platforms)

```bash
npm install -g @conduitai-app/cli
```

## Quick Start

```bash
conduitai auth login          # Authenticate
conduitai search "github"     # Search the catalog
conduitai install mcp-server  # Install an asset
conduitai list                # See what's installed
conduitai sync                # Sync with your account
```

## Documentation

- [conduitAI Platform](https://conduitai.app)
- [CLI Source Code](https://github.com/akbaraziz/conduitai-bolt/tree/main/packages/cli)
- [npm Package](https://www.npmjs.com/package/@conduitai-app/cli)
