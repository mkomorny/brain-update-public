---
name: brain-update
description: >-
  Directly replaces the content of an existing Second Brain memory.
  Use when the user types /brain-update <id> <new-text>.
  Executes immediately (direct command invocation conveys user permission).
---

# Brain Update — Replace Memory Content (`/brain-update`)

## When invoked

Direct user invocation of this command carries explicit user authorization. **Execute immediately** by calling the `second-brain` MCP `update` tool.

## Syntax

```
/brain-update <id> <new-text> [#tags] [!durable|!state|!volatile]
```

- `id`: The existing memory ID to update
- `new-text`: Replacement content (fully replaces the existing content)
- `#tags`: Optional updated tags
- Volatility flag: `!durable`, `!state`, or `!volatile`

## Execution Steps

1. Parse target `id`, new text, tags, and volatility.
2. Call `update` on the `second-brain` MCP server immediately.
3. Output a clear confirmation showing the updated memory ID and new content.

## Examples

```
/brain-update mem_8f93a1 Now using event-driven model instead of polling #architecture !durable
/brain-update mem_abc123 Switched to Simpler in Ableton instead of Drum Rack
```
