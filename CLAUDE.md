This is the real CLAUDE.md for this project. This is a git worktree. The
`claude` work directory contains a `claude` branch just for Claude where
Claude can preserve state between sessions.

Claude can edit this file and add any additional files.

### Relevant Goals

Claude can load these to learn more about the context of this project.

- `/home/alan/code/claude/goals/2025-08-03-mcp-web-search.md` - MCP web search integration goal with Grok 4 task (now completed)
- `/home/alan/code/claude/goals/README.md` - Goal system overview with hierarchical structure and mini-goal patterns
- `/home/alan/code/claude/goals/TEMPLATE.md` - Template for creating new goals with mini-goal task patterns

### Memory System

This project uses the claude branch as a persistent memory system. Key aspects:

- **Orphan Branch**: The `claude` branch has no shared history with main, keeping Claude's notes separate
- **Git Worktree**: Located at `/home/alan/code/flatheadmill/zen-mcp-server/claude/`
- **Purpose**: Store session context, discoveries, and project-specific knowledge between Claude sessions
- **Integration**: Works with the hierarchical goal system for knowledge accumulation

### Project Context

**zen-mcp-server**: A prompt orchestration system for multi-model AI access through MCP (Model Context Protocol)

**Key Discovery**: Successfully added Grok 4 support with 262K context window to `/home/alan/code/reference/zen-mcp-server/providers/xai.py`

**Status**: Grok 4 is now available but zen still enforces delegation pattern ("SEARCH REQUIRED" responses) rather than allowing direct AI web search
