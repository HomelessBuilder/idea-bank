# Idea Bank — Capture System

*This is the overseer's quick-capture system for ideas that surface during
active development work. Low friction is the entire point.*

---

## What This Is

A repository for ideas that arrive at the wrong time — during a session
focused on something else, mid-conversation, mid-build. The idea is worth
keeping; the current session is not the place to develop it. Capture it
here and move on.

This system is recursive by design: it is itself an idea about how to
build systems, used to capture ideas about how to build systems.

---

## How to Use It

When Diego says **"save this for later"** (or similar), the overseer:

1. Drops the idea into `IDEA-LOG.md` immediately — one entry, no ceremony
2. Tags it with a source project and a rough category
3. Returns to whatever was happening before — the capture takes under a minute

Filing into `themes/` or `by-project/` happens later, when there's time,
not in the moment of capture. The log is always the first stop.

---

## Entry Format (IDEA-LOG.md)

```
## IDEA-[NNN] — [Short Title]
*Date: YYYY-MM-DD | Source: [project or session] | Tag: [category]*

[The idea — however brief or detailed it arrived. Diego's words if possible.
Enough context that it makes sense six months from now without needing the
original conversation.]

---
```

**Tag options (loose — add new ones as needed):**
- `course` — ai-foundations-lab content or pedagogy
- `infrastructure` — devlog-engine, monitor, logging systems
- `meta-system` — overseer coordination, automation, self-improvement
- `brand` — Homeless Builder content, narrative, media
- `business` — sandiegoai.help, client work, revenue
- `tool` — new tool concept, Claude Code pattern, workflow improvement
- `ux` — interface, student experience, interaction design
- `unsorted` — no clear category yet, file it and decide later

---

## Folder Structure

```
idea-bank/
├── CLAUDE.md          ← this file
├── VISION.md          ← founding philosophy
├── IDEA-LOG.md        ← all ideas, append-only, newest first
├── themes/            ← named theme folders added as patterns emerge
├── by-project/        ← idea files organized by source project
└── unsorted/          ← ideas without a clear home yet
```

`themes/` and `by-project/` start empty. They fill as the log grows and
patterns become obvious. Nothing is forced into a category that doesn't
exist yet.

---

## Standing Rules

- No deletions without explicit instruction — even half-formed ideas stay
- Ideas are captured in Diego's words wherever possible, not paraphrased
- The log is append-only — never edit an existing entry, only add new ones
- Filing is optional and never urgent — the log is always authoritative
