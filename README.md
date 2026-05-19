# socialpulse-mcp

Social media sentiment & brand monitoring for AI agents u2014 scan mentions, analyze sentiment, track trends, compare competitors, detect spikes, identify influencers, and generate weekly health reports. Powered by local LLM (Gemma 3).

## Quick Start

```bash
git clone https://github.com/marilynceo/socialpulse-mcp.git
cd socialpulse-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://socialpulse.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/socialpulse-mcp

# Or connect directly via MCP client
# Endpoint: https://socialpulse.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
