# PROCESS.md - QFit Website Development Process

> This document describes how we work on the QFit website project.
> It applies to all sessions, all features, all contributors.
> Claude Code reads this document at the beginning of every session.
> Based on the process developed in the Nessieat project (Piksel Home Project).

---

## Core Principle

> We don't just start coding.
> Every section starts as an idea, becomes a User Story,
> gets reviewed, lands in the backlog, and is then developed.
> Documentation is not an afterthought - it is part of the work.

---

## 1. Feature Process

```
1. IDEA          Product Owner describes informally in plain language
        ↓
2. USER STORY    Claude formulates a structured User Story
                 with acceptance criteria
        ↓
3. REVIEW        Product Owner and Claude review together
        ↓
4. BACKLOG       User Story goes into BACKLOG.md
        ↓
5. DEVELOPMENT   Claude Code implements the section
        ↓
6. REVIEW        View result in browser and review
        ↓
7. CLOSE         Docs updated, code committed
```

### Key Rule
> No development without a User Story in the backlog.
> No User Story without review by the Product Owner.

---

## 2. Design Process

```
1. Create Stitch prompt (together in claude.ai)
        ↓
2. Google Stitch generates design proposals
        ↓
3. Product Owner reviews and chooses direction
        ↓
4. DESIGN.md is updated
        ↓
5. Claude Code builds sections according to DESIGN.md
```

### WordPress Consideration
> Every design decision must consider the WordPress handoff.
> Avoid overly complex JavaScript interactions.
> Prefer clean HTML structure that is easy to convert.

---

## 3. Session Process

### Starting a session
```bash
cd ~/Documents/Piksel/qfit-website
git pull
claude
```

First message:
```
Please read all documents in the docs/ folder and tell me where we stand.
```

### During the session
- Product Owner sets direction and makes decisions
- Claude Code develops, tests, documents
- Complex questions / planning: discuss in claude.ai

### Ending a session
Claude Code updates independently:
- CLAUDE.md - session log, status, next step
- APP_AS_IS.md - when sections are completed
- BACKLOG.md - when User Story status changes
- DESIGN.md - when design decisions are made

Then commit:
```bash
git add .
git commit -m "session: [short description]"
git push
```

---

## 4. Documentation Rule

> Docs are always current.
> Claude Code updates all affected documents at the end of every session
> independently and without explicit instruction.

| Document | Updated when... |
|----------|----------------|
| CLAUDE.md | Every session |
| APP_AS_IS.md | A section is completed |
| BACKLOG.md | User Story status changes |
| DESIGN.md | Design decision made |
| CONTENT.md | Text content is added or changed |
| PROCESS.md | Process is changed |

---

## 5. WordPress Handoff Process

When a section is complete and ready for WordPress:

1. Section is marked as Done in BACKLOG.md
2. HTML is clean, well-commented, and self-contained
3. All SVG graphics are optimized and documented
4. CONTENT.md contains all text content separately
5. Colleague is notified via GitHub (Issue or PR)

---

## 6. Commit Message Format

```
[type]: [short description]

Types:
- feat: new section or feature
- fix: bug fix
- docs: documentation update
- style: design changes
- content: text content changes
- session: session update
```

---

*Last updated: 2026-04 - Initial version based on Nessieat project process*
