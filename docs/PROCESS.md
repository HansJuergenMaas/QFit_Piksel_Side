# PROCESS.md - QFit Website Development Process

> This document describes how we work on the QFit website project.
> It applies to all sessions, all features, all contributors.
> Read at the beginning of every session as needed.
> Based on the process developed in the Nessieat project — extended for role-based Design approach.

---

## Core Principle

> We don't just start coding.
> Content is defined before design. Design is confirmed before code.
> Each phase has its own tool. The tools do not overlap.
> Documentation is not an afterthought — it is part of the work.

---

## 1. The Three-Tool Workflow

```
TOOL 1: claude.ai Chat
— Strategy, information architecture, content decisions
— Persona definitions, copy, briefing preparation
— All planning happens here before anything is built

        ↓

TOOL 2: Claude Design
— Visual prototyping, section by section
— One persona at a time, fully before moving to next
— Briefings come from claude.ai chat — never improvised

        ↓

TOOL 3: Claude Code
— HTML + Tailwind CSS implementation
— Only starts after design is confirmed by PO
— Git commits, documentation updates
```

### Critical Rule
> Claude Code does NOT start until Claude Design prototypes are reviewed
> and the design direction is confirmed by the Product Owner.
> Building code on an unconfirmed design wastes time and tokens.

---

## 2. Phase Process

### Phase 1 — Content & Architecture (claude.ai Chat)
```
1. Define personas and their problems
2. Define information architecture (page structure per role)
3. Write content per section per persona
4. Prepare Claude Design briefings
5. PO reviews and confirms content direction
```

### Phase 2 — Design Prototyping (Claude Design)
```
1. Start new Claude Design session
2. Paste Design System briefing first
3. Request design proposal — do NOT build directly
4. Confirm design direction with PO
5. Build section by section — one persona at a time
6. PO reviews after each section — feedback before next
7. Complete one persona fully before starting next
8. Export as zip / HTML when persona is complete
9. Repeat for each persona
10. PO reviews all personas together — confirm direction
```

### Phase 3 — Implementation (Claude Code)
```
1. Claude Code reads all docs in docs/ folder
2. Implements confirmed design into index.html
3. Integrates real logo SVG and product UI screens
4. Adds interactive elements (toggle mechanic, animations)
5. Tests on mobile and desktop
6. Updates all affected docs
7. Git commit
8. WordPress handoff preparation
```

---

## 3. Claude Design — Working Rules

- **Never ask Design to build everything at once** — always section by section
- **Always show design proposals first** — not a finished build
- **Always state clearly** what persona is active and what must NOT be changed
- **Parallel personas** — place side by side, not stacked, for comparability
- **Export** — use zip export via prompt, not the download button (unreliable)
- **Usage limit** — Design has a separate weekly limit that resets Saturday.
  Batch sections efficiently: combine 2 small sections per prompt to save tokens
- **Freeze before moving on** — explicitly state "do not modify X" in every prompt

### Prompt Structure for Design Sessions
```
1. State what is frozen (do not touch)
2. State what persona is active
3. State which section(s) to build
4. Provide full design spec (copy, colors, layout, icons)
5. End with: "Show me this section. I will give feedback before we continue."
```

---

## 4. Session Process

### Starting a session (claude.ai Chat)
Read CLAUDE.md to know current status.
First message to Claude Code (when in Code phase):
```
Please read all documents in the docs/ folder and tell me where we stand.
```

### During a session
- PO sets direction and makes decisions
- claude.ai Chat: strategy, content, briefing prep
- Claude Design: visual work, section by section
- Claude Code: implementation only after design confirmed

### Ending a session
Update all affected docs:
- CLAUDE.md — session log, current status, next step
- APP_AS_IS.md — what is now complete
- BACKLOG.md — status changes
- DESIGN.md — if design decisions were made
- CONTENT.md — if copy was finalized
- PROCESS.md — if process changed

Then commit (Claude Code phase only):
```bash
git add .
git commit -m "session: [short description]"
git push
```

---

## 5. Documentation Rule

> Docs are always current.
> All affected documents are updated at the end of every session.

| Document | Updated when... |
|----------|----------------|
| CLAUDE.md | Every session |
| APP_AS_IS.md | A section or prototype is completed |
| BACKLOG.md | Status of any item changes |
| DESIGN.md | Design decisions are confirmed |
| CONTENT.md | Copy is finalized for any section |
| VISION.md | Strategic direction changes |
| PROCESS.md | Process itself changes |
| FEATURES.md | Page structure changes |

---

## 6. Persona Content Rule

> Each persona has a complete content definition before Claude Design touches it.
> The content definition lives in claude.ai chat history and is summarized in CONTENT.md.
> Claude Design receives a full briefing — it never invents content.

---

## 7. WordPress Handoff Process

When all sections are complete and confirmed:

1. All sections marked Done in BACKLOG.md
2. HTML is clean, well-commented, and self-contained
3. All SVG graphics optimized and documented
4. CONTENT.md contains all text content separately
5. DESIGN.md documents all Tailwind classes and CSS equivalents
6. Colleague notified via GitHub

---

## 8. Commit Message Format

```
[type]: [short description]

Types:
- feat: new section or feature
- fix: bug fix
- docs: documentation update
- style: design changes
- content: text content changes
- session: end-of-session update
```

---

*Last updated: 2026-04-23 — Extended for three-tool workflow (Chat → Design → Code)*
