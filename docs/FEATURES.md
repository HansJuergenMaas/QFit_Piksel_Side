# FEATURES.md - QFit Website Features & Page Structure

> This document describes the confirmed page structure and feature set.
> It is the reference for User Stories in BACKLOG.md and implementation in Claude Code.
> Updated: 2026-04-23 — fully defined based on role-based architecture decision.

---

## Website Type

**Single page** with role-based persona toggle.
The toggle is set in the Hero and drives content adaptation throughout the page.
No separate pages per persona — one URL, one scroll, adapted content per role.

---

## Page Sections — Confirmed Structure

### Universal Sections (same content for all personas)

| # | Section | Description | Priority |
|---|---------|-------------|----------|
| Nav | Navigation bar | Sticky, logo + links + CTA button | High |
| 03 | What QFit Is | Blockquote anchor + 3 descriptors + stats row | High |
| 04 | How It Works | 4-step horizontal stepper + detail cards | High |
| 09 | Call to Action | Final conversion — 2 buttons + contact | High |
| 10 | Footer | Logo, links, legal, contact | Medium |

### Role-Specific Sections (content adapts per persona toggle)

| # | Section | Adaptation type | Priority |
|---|---------|----------------|----------|
| 01 | Hero | Sub-headline changes per persona | High |
| 02 | The Problem | Completely different content per persona | High |
| 05 | Use Cases | Tab layout — each persona has full content | High |
| 06 | The Science | Different metrics emphasized per role | Medium |
| 07 | Platform Capabilities | Different features prioritized per role | High |
| 08 | Technology | Depth and framing varies per role | Medium |

### Removed Sections (confirmed — not included)

| Section | Reason |
|---------|--------|
| Pricing | Sales conversation only — not website content |
| Market & Traction | Investor material — not for general landing page |
| Team & Locations | Low priority — can be added as optional later |

---

## Persona Toggle — 4 Roles

| ID | Label in toggle | Primary audience |
|----|----------------|-----------------|
| P1 | Athletes & Trainers | Individual athletes, personal trainers |
| P2 | Gyms & Fitness Clubs | Gym owners, fitness club managers |
| P3 | Sports Clubs & Schools | S&C coaches, club directors, schools |
| P4 | Equipment Manufacturers | Fitness equipment brands |

---

## Section Specifications

### Navigation Bar
- Sticky, top-0, white background with backdrop blur
- Left: QFit logo
- Center: How it works · Features · Use cases · About
- Right: "Get started" — primary button
- Mobile: collapses to hamburger

### Hero
- 2-column layout: text left, app visual right
- Eyebrow: "DIGITAL GYM APPLICATION"
- Headline: "Better workouts. Guaranteed." (gradient on "Guaranteed.")
- Persona toggle pills (4 roles) — active role drives sub-headline
- 2 CTAs: "Get started" (primary) + "See how it works" (ghost)
- Right: dark app dashboard panel (placeholder → real SVG screens in Code phase)

### The Problem
- Headline adapts per persona
- 4 problem cards (bento grid) — different content per persona
- Cards: icon + title + description

### What QFit Is (Universal)
- Blockquote: "QFit is not content. It is training intelligence."
- 3 columns: Intelligence layer · Goal-focused · Automated & scalable
- Stats row: 2,000+ exercises · 11 goals · relevant stat 3 · relevant stat 4

### How It Works (Universal)
- Headline: "From goals to results — four steps."
- Horizontal stepper: Assessment → Goals → Equipment → AI Plan
- Step 4 highlighted as the "magic moment"
- 2 detail cards below: what QFit learns + what Qi delivers

### Use Cases
- Tab row: 4 persona tabs
- Active tab shows: badge + headline + intro + 4 benefit bullets + CTA
- Right column: role-specific stats cards and/or visual

### The Science
- Headline: "Workout planning is no longer an art. It's a science."
- 4 metric cards selected per persona (from 8 total metrics)
- Each card: metric name + definition + mini chart + relevance tag
- Full 8 metrics available: MEE · F×TuT · MEP · APP · ARV · WTM · WEM · Goal Radar

### Platform Capabilities
- Headline: "Every tool a gym needs. Every insight a member deserves."
- 6 capabilities total — prioritized differently per persona
- 3 primary (highlighted border) + 2-3 secondary cards
- Capabilities: Program Generation · Session Sequencer · Auto-Adaptation ·
  Analytics · LLM Communications · Operational Intelligence

### Technology
- Headline: "Built on real biomechanics. Powered by AI. Integrated into your world."
- Architecture flow diagram: Inputs → QFit AI (Qi) → Outputs
- Integration badges: Garmin · Apple · VALD · VO2Master · Catapult · API-first
- IMU footnote (subtle — extended capability, not primary feature)
- Depth of explanation varies per persona

### Call to Action
- Headline adapts slightly per persona
- Sub-text: persona-relevant
- 2 buttons: "Get started" (primary) + "Request a demo" (ghost)
- Contact: contact@qfit.ai

### Footer
- 4 columns: Brand + Product + Company + Legal
- Logo + tagline + email
- Navigation links
- Copyright: © QFit · Piksel

---

## Interactive / Dynamic Elements

| Element | Type | Status |
|---------|------|--------|
| Persona toggle | JS — drives all role-specific content | To implement in Code phase |
| How It Works stepper | CSS/JS — expandable step detail | To implement |
| Science metric cards | CSS — hover expand option | To decide |
| Use Cases tabs | JS — tab switching | To implement |
| Nav sticky behavior | CSS — backdrop blur on scroll | To implement |
| Scroll animations | CSS — subtle fade-in | To decide |

---

## Graphics & Assets

### Available Now (source_material/Elements/)

| Asset group | Count | Best used in |
|-------------|-------|-------------|
| Session Sequencer — Athlete | 9 iPad + 1 Garmin | How it works, Athlete persona |
| Session Sequencer — Trainer | 3 screens | Trainer persona, Capabilities |
| Workout Plan Generator | 3 screens | How it works, What QFit Is |
| Analytics — Athlete | 3 screens | Science, Athlete persona |
| Analytics — Gym population | 8 screens | Gym persona, Operational intel |
| Analytics — LLM Integration | 2 screens | LLM communications |
| Equipment Library | 2 screens | How it works step 3 |
| Exercise Library | 2 screens | Platform capabilities |

### Logo Files (source_material/)

| File | Use case |
|------|----------|
| Logo_long_Qfit.svg | Nav, footer — needs fill update for light bg |
| Logo_short_QFIT.svg | Favicon, mobile nav |
| Q_fit_grey.png | Light background fallback |

### Designed in Claude Design (placeholders → replace in Code phase)
- Hero dark dashboard panel (per persona variant TBD)
- Goal Radar chart
- Deployment flow diagram (Gym persona)
- Metric mini-charts (WTM line, MEE bars, F×TuT heatmap)
- Architecture flow diagram

---

## WordPress Handoff Checklist

For each completed section:
- [ ] HTML is clean, semantic, well-commented
- [ ] All text documented in CONTENT.md
- [ ] All graphics are optimized SVG or PNG (not embedded in JS)
- [ ] Tailwind classes documented with CSS equivalents in DESIGN.md
- [ ] Section works on mobile and desktop
- [ ] Interactive elements use progressive enhancement

---

*Last updated: 2026-04-23 — Fully defined from role-based architecture decision.
Previous placeholder content replaced entirely.*
