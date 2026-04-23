# CLAUDE.md - QFit Website Project

> This document is read at the beginning of every new session.
> It contains everything Claude needs to know to be immediately productive.
> It is updated at the end of every session.

---

## Project Overview

**Project Name:** QFit Website
**Type:** Marketing / Product website for the QFit fitness app
**Company:** Piksel
**Repository:** https://github.com/HansJuergenMaas/Qfit_Piksel_Side (private)
**Goal:** Role-based marketing website, prototyped in Claude Design,
then implemented in HTML + Tailwind CSS for WordPress handoff (piksel.com)
**Local development folder:** ~/Documents/My-Projects/WebSite/QFit_Piksel_Side

---

## Context: What is QFit?

QFit is an AI-powered fitness platform developed by Piksel.
It is not a content library — it is training intelligence.
It generates personalized workout plans based on individual athlete data,
adapts them after every session, and delivers automated coaching
communication at scale.
Full details: see VISION.md

---

## Who works on this project?

| Person | Role | Notes |
|--------|------|-------|
| Hans-Juergen | Product Owner | Works with Claude as primary development tool |
| Colleague (Piksel) | WordPress implementation | Takes finished prototype into piksel.com |
| Claude (claude.ai chat) | Strategist, Content Architect, Documentarian | Planning, content, briefings, decisions |
| Claude Design | Visual Designer | Builds role-specific prototypes section by section |
| Claude Code | Developer | Implements confirmed design into index.html |

---

## Tool Stack & Roles

| Tool | Role | When |
|------|------|-------|
| claude.ai chat | Strategy, content, decisions, briefing preparation | Always — the planning layer |
| Claude Design | Visual prototyping, section-by-section design | After content is confirmed |
| Claude Code | HTML + Tailwind implementation, Git, docs | After design is confirmed |
| Google Stitch | Initial design direction (Precision Performance) | Done — output used as Design System |
| GitHub | Version control | Active |

**No backend, no Node.js, no Docker needed** — pure frontend website.

---

## Design System — "Precision Performance" (Light)

Confirmed from Stitch proposal (code.html). Key values:

| Element | Value |
|---------|-------|
| Page background | #fcf9f8 (warm off-white) |
| Section alternates | #f0eded / #ffffff / #f6f3f2 |
| Cards | bg #f3f4f6, border #e5e7eb, hover border #4ece7a |
| Primary color | #006d36 (dark green — text, icons) |
| Primary container | #4ece7a (mid green — buttons, highlights) |
| Gradient | #6be87a → #3dd9a4 (logo, glow, accents) |
| Heading font | Manrope — weights 600/700/800 |
| Body font | Inter — weights 400/500/600 |
| Border radius | Cards: 12px · Buttons: rounded-full · Sections: rounded-[40px] |
| Icons | Material Symbols Outlined |

Dark panel (hero app visual only): bg #313030, rounded-xl —
intentional dark/light contrast element within the light page.

---

## Information Architecture — Role-based

The website uses a **persona toggle** that adapts content per role.
The toggle is set in the Hero and remains active throughout the page.

### 4 Personas

| ID | Persona | Primary Problem |
|----|---------|----------------|
| P1 | Athletes & Trainers | Generic programs, no real feedback, invisible injury risk |
| P2 | Gyms & Fitness Clubs | Churn in 90–120 days, trainers don't scale, no operational visibility |
| P3 | Sports Clubs & Schools | Individual conditioning for a whole squad, injury prevention at population level |
| P4 | Equipment Manufacturers | Hardware alone no longer differentiates — no training intelligence |

### Page Structure

| Section | Type | Notes |
|---------|------|-------|
| Navigation | Universal | Sticky, dark on light |
| Hero + Toggle | Universal | Sub-headline adapts per persona |
| The Problem | Role-specific | Adapts per persona via toggle |
| What QFit Is | Universal | Anchor statement — same for all |
| How It Works | Universal | 4-step stepper — same for all |
| Use Cases | Role-specific | Tab layout, full persona depth |
| The Science | Role-weighted | Different metrics emphasized per role |
| Platform Capabilities | Role-weighted | Different features prioritized per role |
| Technology | Role-weighted | Depth varies per role |
| CTA | Universal | Two buttons: Get started + Request a demo |
| Footer | Universal | Standard |

**Pricing removed** — not included in website. Sales conversation only.

---

## Development Principles

1. **Content before Design:** Information architecture and copy are confirmed
   in claude.ai chat before Claude Design builds anything
2. **Design before Code:** Claude Design prototypes each role visually.
   Claude Code only starts after design is confirmed
3. **Role-by-role:** Each persona is prototyped completely before moving
   to the next
4. **Documentation-as-Context:** Every session starts by reading all docs
5. **Docs are always current:** All affected documents updated at end of session
6. **WordPress-compatibility:** Every decision considers the eventual handoff
7. **No secrets in repo:** API keys etc. only in .env files

---

## Documents to read at the start of every session

| Document | Purpose | Always read? |
|----------|---------|--------------|
| docs/CLAUDE.md | This file — project overview and current status | Yes |
| docs/APP_AS_IS.md | Current state of all deliverables | Yes |
| docs/BACKLOG.md | Open work items per phase | Yes |
| docs/DESIGN_BRIEFINGS.md | Ready-to-paste Claude Design prompts | Yes — for Design sessions |
| docs/VISION.md | What the QFit website should show | Yes |
| docs/DESIGN.md | Design system details | Yes |
| docs/PROCESS.md | Development process and rules | As needed |
| docs/CONTENT.md | All confirmed copy per persona | As needed |

---

## How to start the next Claude Design session (from Saturday)

**Step 1 — Open this chat or a new claude.ai chat:**
Read CLAUDE.md + APP_AS_IS.md + DESIGN_BRIEFINGS.md

**Step 2 — Open claude.ai/design**

**Step 3 — Paste the SESSION OPENER from DESIGN_BRIEFINGS.md first**
This reestablishes context so Design knows the current state.

**Step 4 — Paste briefings in order from DESIGN_BRIEFINGS.md:**
- ATH-BLOCK-A → ATH-BLOCK-B → ATH-BLOCK-C (completes Athlete)
- CLB-BLOCK-A → CLB-BLOCK-B → CLB-BLOCK-C (Sports Club)
- EQP-BLOCK-A → EQP-BLOCK-B → EQP-BLOCK-C (Equipment Mfr.)
- FINAL STEP → 4-column comparison view

All briefings are complete, self-contained, and ready to paste.
No preparation needed — open DESIGN_BRIEFINGS.md and go.

---

## Current Project Status

**Phase:** 2 — Design Prototyping (Claude Design)
**Last update:** 2026-04-23

**What is done:**
- Design system confirmed (Precision Performance — light theme)
- Information architecture defined — role-based toggle approach
- Content architecture fully worked out for all 4 personas — see CONTENT.md
- All Claude Design briefings prepared for all remaining sections — see DESIGN_BRIEFINGS.md
- Gym & Fitness Club prototype: complete (all sections) — exported as zip
- Athlete & Trainer prototype: Hero + Problem only (usage limit reached)

**What is next (from Saturday when Design limit resets):**
- Open claude.ai/design
- Follow the SESSION OPENER + briefing sequence in DESIGN_BRIEFINGS.md
- Complete Athlete & Trainer (ATH-BLOCK-A, B, C)
- Build Sports Club & School (CLB-BLOCK-A, B, C)
- Build Equipment Manufacturer (EQP-BLOCK-A, B, C)
- Build 4-column comparison view (FINAL STEP)
- Review all 4 prototypes with team
- Confirm design direction → Claude Code implementation begins

---

## Session Log

| Date | What was done | Next step |
|------|--------------|-----------|
| 2026-04 | Project started, initial docs created | Bring in source materials |
| 2026-04-22 | Read all source material. Wrote VISION.md. Confirmed design system. Received Stitch proposal. | Confirm design direction |
| 2026-04-23 | Confirmed Stitch proposal (light theme). Defined role-based information architecture. Worked out full content for all 4 personas. Built Gym prototype in Claude Design (complete). Started Athlete prototype (Hero + Problem). Hit Design usage limit. | Saturday: complete Athlete + build Sports Club + Equipment Mfr. |

---

*This document is updated at the end of every session.*
