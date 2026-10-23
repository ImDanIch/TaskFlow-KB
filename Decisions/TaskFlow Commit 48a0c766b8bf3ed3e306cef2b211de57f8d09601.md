---
type: decision
---
# Implement MCP integrations for TaskFlow

Commit: `48a0c766b8bf3ed3e306cef2b211de57f8d09601`
Message: Implement MCP integrations for TaskFlow
Source: https://github.com/ImDanIch/TaskFlow/commit/48a0c766b8bf3ed3e306cef2b211de57f8d09601

## Changed files

- `README.md` (modified)
- `mcp_server/README.md` (added)
- `mcp_server/__init__.py` (added)
- `mcp_server/requirements.txt` (added)
- `mcp_server/server.py` (added)
- `mcp_server/vault.py` (added)
- `tests/test_mcp_stdio.py` (added)
- `tests/test_mcp_vault.py` (added)

## Summary

Adds a local stdio MCP server exposing search_notes, get_note, and ingest_note for a configured Markdown vault. Implements vault path checks, adds vault and stdio integration tests, and documents setup and verified MCP usage.
