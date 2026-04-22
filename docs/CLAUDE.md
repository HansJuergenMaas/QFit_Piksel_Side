# CLAUDE.md - QFit Website Project

> This document is read at the beginning of every new session.
> It contains everything Claude needs to know to be immediately productive.
> It is updated by Claude Code independently at the end of every session.

---

## Project Overview

**Project Name:** QFit Website
**Type:** Marketing / Product website for the QFit fitness app
**Company:** Piksel
**Repository:** https://github.com/HansJuergenMaas/qfit-website (private)
**Goal:** HTML + Tailwind CSS prototype to serve as a template for WordPress (piksel.com)
**Local development folder:** ~/Documents/Piksel/qfit-website

---

## Context: What is QFit?

QFit is a fitness app developed by Piksel that uses AI.
Full details: see VISION.md and FEATURES.md

---

## Who works on this project?

| Person | Role | Notes |
|--------|------|-------|
| Hans-Juergen | Product Owner | Works with Claude as primary development tool |
| Colleague (Piksel) | WordPress implementation | Takes finished prototype into piksel.com |
| Claude | Developer, Designer, Documentarian | Reads this document at the start of every session |

---

## Tech Stack

| Layer | Technology | Reason |
|-------|------------|--------|
| Frontend | HTML + Tailwind CSS | Simple, no backend needed, easy WordPress handoff |
| Graphics | SVG | Already started, scalable, web-ready |
| Version control | GitHub | Collaboration, history |
| Design tool | Google Stitch | AI-assisted design (same approach as Nessieat project) |

**No backend, no Node.js, no Docker needed** - pure frontend website.

---

## Existing Materials

| Material | Format | Status |
|----------|--------|--------|
| QFit app description | PPT | Available - basis for content |
| Structured web page | HTML | Already started |
| SVG graphics | SVG | Partially created |

---

## Development Principles

1. **Documentation-as-Context:** Every session starts by reading all docs
2. **Feature development via User Stories:** New sections/features only through documented User Stories
3. **Docs are always current:** Claude Code updates all affected documents independently at end of each session
4. **Design-First:** Design is developed with Stitch and documented in DESIGN.md
5. **WordPress-compatibility:** Every decision considers the eventual handoff to WordPress
6. **No secrets in repo:** API keys etc. only in .env files

---

## Documents to read at the start of every session

| Document | Purpose | Always read? |
|----------|---------|--------------|
| docs/VISION.md | What the QFit website should show | Yes |
| docs/APP_AS_IS.md | Current state of the website | Yes |
| docs/BACKLOG.md | Open sections and User Stories | Yes |
| docs/FEATURES.md | Planned pages and content | Yes |
| docs/DESIGN.md | Design system (after Stitch session) | Yes |
| docs/PROCESS.md | Development process and rules | As needed |
| docs/CONTENT.md | Texts and content for the website | As needed |

---

## Current Project Status

**Phase:** 0 - Setup
**Last update:** Project started
**Next step:** Bring in existing materials, define vision, develop design with Stitch

---

## Session Process

### Starting a new session
```bash
cd ~/Documents/Piksel/qfit-website
git pull
claude
```

First message to Claude Code:
```
Please read all documents in the docs/ folder and tell me where we stand.
```

### Ending a session
Claude Code updates all affected docs independently. Then:
```bash
git add .
git commit -m "session: [short description]"
git push
```

---

## Session Log

| Date | What was done | Next step |
|------|--------------|-----------|
| 2026-04 | Project started, initial docs created | Bring in existing materials, define vision |

---

*This document is updated by Claude Code at the end of every session.*
