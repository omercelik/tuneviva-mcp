# TuneViva MCP connector

Connect an MCP client to the hosted [TuneViva](https://tuneviva.com/) service at `https://tuneviva.com/mcp`. This repository contains marketplace metadata for the hosted service; it does not contain the server implementation.

## Tools

- `search_sheet_music` creates a search link for a composer or work. Open the link to inspect results.
- `get_practice_score` retrieves details and practice and MusicXML links for a supported numeric score ID.
- `scan_sheet_music` explains how to use TuneViva’s browser-local printed music scanner. It does not upload or process an image through MCP.

The endpoint uses Streamable HTTP and requires no account or API key. See the [TuneViva API documentation](https://tuneviva.com/docs/api) for the practice score API.

Example MCP configuration:

```json
{"mcpServers":{"tuneviva":{"url":"https://tuneviva.com/mcp"}}}
```
