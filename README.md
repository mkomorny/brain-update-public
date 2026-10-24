# Brain Update

> **Tri-Platform Agent Skill** for Claude Desktop / Code, Grok CLI, and Google Antigravity / Gemini.  
> In-Place Content Update for Existing Memory Records — Directly replaces the content of an existing Second Brain memory record while maintaining its ID, links, and history.

---

## Overview

`brain-update` provides standardized capabilities across conversational AI platforms:
- In-place memory content replacement (/brain-update <id> <new-text>).
- Direct slash command invocation conveying user authorization.
- Confirmation report displaying updated content and preserved connections.
- Tri-platform NTFS junctions connecting Claude, Grok, and Antigravity.
- Standard documentation suite: SKILL.md, HOW_TO_USE.txt, IMPLEMENTATION_PLAN.md, and README.md.

---

## Tri-Platform Architecture

Zero duplicate code across platforms. Canonical source resides in `.agents`:
- **Canonical Source**: `C:\Users\<you>\.agents\skills\brain-update`
- **Claude**: `C:\Users\<you>\.claude\skills\brain-update` (NTFS Junction)
- **Grok**: `C:\Users\<you>\.grok\skills\brain-update` (NTFS Junction)
- **Antigravity**: `C:\Users\<you>\.gemini\config\skills\brain-update` (NTFS Junction)

---

## Documentation Suite

- [`HOW_TO_USE.txt`](HOW_TO_USE.txt): Standardized user guide and prompt templates.
- [`IMPLEMENTATION_PLAN.md`](IMPLEMENTATION_PLAN.md): Feature checklist and roadmap.
- [`App Changes Tracker.html`](App%20Changes%20Tracker.html): Interactive visual version log.
- [`SKILL.md`](SKILL.md): Agent system instructions and triggers.
