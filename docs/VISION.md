# VISION.md — QFit Website

> This document is the north star for all design and content decisions.
> Every section, every headline, every design choice should serve this vision.
> Updated: 2026-04-23 — page structure and open questions updated.

---

## What is QFit?

QFit is an AI-powered fitness platform developed by Piksel. It does not deliver workout content — it delivers **training intelligence**. This distinction is the sharpest differentiator in all source material and must run through every page of the website.

At its core, QFit is a biomechanics model (200+ bones, 600+ muscles modelled) combined with an AI engine (QFit AI, branded "Qi") that generates fully individualized workout programs, sequences live training sessions, tracks performance against meaningful physiological metrics, and scales personalized coaching from one athlete to 100,000 gym members — automatically.

**The anchor tagline, confirmed across all source decks, is:**
> *"Better workouts. Guaranteed."*

**The positioning line:**
> *"QFit is not content. It is training intelligence."*

Neither of these should be changed without broader alignment with the QFit team.

---

## The Problem QFit Solves

The fitness industry has a structural mismatch: members arrive with individual bodies, individual goals, and individual histories, while the tools available to serve them — group classes, generic programs, over-stretched trainers — were never designed for that diversity. This creates four compounding problems:

1. **Generic training** — video libraries and group classes cannot adapt to physiology, injury history, or individual goals
2. **Trainers don't scale** — personalized coaching is expensive and capacity-limited
3. **High early churn** — members disengage in the first 90–120 days when results, guidance, and communication are absent
4. **No operational visibility** — gym operators have limited data on member progress, equipment usage, or outcomes

QFit addresses all four simultaneously.

---

## Purpose of This Website

The QFit website serves four purposes:

1. **First impression** — instantly communicate what QFit is and why it matters, for any visitor regardless of background
2. **Product showcase** — demonstrate the platform's depth, features, and scientific foundations
3. **Persona branching** — guide different types of visitors into a view of QFit that is relevant to their specific role and interests
4. **Lead generation** — drive demo requests, sign-ups, and direct contact

The website is built as an HTML + Tailwind CSS prototype (via Claude Design + Claude Code)
that will be handed off to a Piksel colleague for implementation in WordPress on piksel.com.
Every design and content decision must account for this handoff.

---

## Core Information Architecture

The website uses a **persona toggle** that is set in the Hero and drives all role-specific
content throughout the page. The toggle approach was confirmed over a static tab approach
because it is the most honest reflection of QFit's own personalization philosophy.

### Universal sections (all personas see the same content)

- **Hero** — tagline + persona toggle + first CTA
- **What QFit Is** — positioning, three core descriptors, key statistics
- **How It Works** — four-step plan generation process

### Role-specific sections (content adapts per toggle)

- **The Problem** — each persona has their own problem framing
- **Use Cases** — tab layout with full persona depth per role
- **The Science** — different metrics emphasized per role
- **Platform Capabilities** — different features prioritized per role
- **Technology** — depth varies per role

### Universal closing sections

- **CTA** — two buttons: Get started + Request a demo
- **Footer** — navigation, legal, contact

---

## Target Audience — Personas in Detail

### Persona 1: Athletes & Trainers
*Individual performance focus*

An athlete wants a plan that actually fits them — not a generic 12-week program. They want to know their training is moving the needle toward their specific goals (strength, hypertrophy, power, endurance, mobility — 11 goal types supported). They want session guidance, feedback that tells them how the workout actually went, and a program that adapts when things change.

A personal trainer wants to deliver that level of quality to every client without spending hours building programs and spreadsheets.

**Core problem:** Generic programs, no real feedback after sessions, invisible injury risk, trainer admin overload.

**Key message:** *QFit builds your training plan around your body, your goals, and your available time — then tracks every session with the metrics that actually matter. No guesswork. No generic programs. Just measurable progress, every workout.*

### Persona 2: Gyms & Fitness Clubs
*Scale and retention focus*

A gym owner's problem is the gap between the diverse membership they have and the personalized coaching those members expect. They can't hire enough trainers to close it. The result is churn — most prominently in the first 90–120 days. They also lack data: they don't know what's working, which equipment is being used, or whether their members are progressing.

**Core problem:** Churn in 90–120 days, personalization doesn't scale, no operational visibility, communication is manual.

**Key message:** *QFit is the training intelligence layer that closes the gap between your diverse membership and the personalized coaching they expect — without scaling your trainer headcount.*

The gym deployment model follows a four-stage path: Pilot → Validate → Expand → Full deployment.

### Persona 3: Sports Clubs & Schools
*Team conditioning and testing focus*

A sports club director or S&C coach has a squad of athletes with vastly different physical profiles. They need individual conditioning plans for each, population-level assessments (VO2max, CMJ, 1RM), and early warning of injury risk before it becomes a problem.

**Core problem:** Individual conditioning for an entire squad is manually impossible, injury risk invisible at population level, no shared data layer between trainer / coach / medical.

**Key message:** *Individual conditioning plans for every athlete on your squad. Population analytics for the whole team. Injury risk flagging before it becomes a problem.*

### Persona 4: Equipment Manufacturers
*Integration and differentiation focus*

A fitness equipment manufacturer wants their hardware to be smarter. QFit's API-first architecture means it can sit as an intelligence layer on top of any equipment ecosystem — capturing real-time session data, enriching it with biomechanical metrics, and feeding it back to athletes and operators.

**Core problem:** Hardware alone no longer differentiates. No training intelligence in the device. No usage data feeding back to product development.

**Key message:** *API-first design means QFit connects to your existing ecosystem without disruption. No rip-and-replace. Works alongside what you already have. Your hardware becomes a platform.*

---

## Key Messages (fixed — do not change without team alignment)

| Message | Usage |
|---------|-------|
| "Better workouts. Guaranteed." | Hero tagline — anchor of the entire page |
| "QFit is not content. It is training intelligence." | Positioning — opens What QFit Is section |
| "From goals to gains — four steps." | How It Works headline |
| "Workout planning is no longer an art. It's a science." | The Science section headline |
| "Every tool a trainer needs. Every insight an athlete deserves." | Platform Capabilities headline |
| "Built on real biomechanics. Powered by AI." | Technology section headline |
| "Ready to make every membership count?" | CTA — Gym persona variant |
| "Ready to make your workouts better — guaranteed?" | CTA — universal variant |

---

## Key Statistics (confirmed across Jan 2026 + March 2025 decks)

| Stat | Meaning |
|------|---------|
| 2,000+ exercises | Exercise library depth |
| 11 athletic goals | Goal types the AI can optimize for |
| 600+ muscles modelled | Biomechanics model resolution |
| 17 onboarding steps | Depth of athlete assessment |
| 9 data categories | What the onboarding captures |
| 200+ bones modelled | Biomechanics model coverage |

---

## Science & Metrics Layer

QFit tracks metrics that traditional training tools don't calculate.
These are a core differentiator and should be presented in accessible (not academic) language.

| Metric | What it measures | Primary persona |
|--------|----------------|----------------|
| **MEE** | Mechanical Energy — total work in kcal | Athlete, Gym |
| **F×TuT** | Force × Time under Tension — hypertrophy/strength driver | Athlete, Club |
| **MEP** | Metabolic Efficiency — adaptation over time | Athlete |
| **APP** | Average Peak Power — power-sport athletes | Club |
| **ARV** | Average Rep Velocity — zone-based prescription | Athlete, Club |
| **WTM** | Wear & Tear Metric — cumulative joint load, injury signal | All |
| **WEM** | Workout Efficiency Metric — TuT ratio, time optimization | Athlete, Gym |
| **Goal Radar** | Visual plan-to-goal match score | All |

---

## Technology Overview

**Architecture:** Inputs → QFit AI (Qi) → Outputs

- Inputs: athlete metadata, equipment library, exercise library (2,000+), wearable data
- Outputs: workout plan, session sequencer, analytics & reporting, LLM communications

**Integration partners (confirmed):** Garmin, Apple, VALD, VO2Master, Catapult, + open API

**IMU:** Extended capability — precision motion capture. Treated as subtle footnote,
not a primary feature. Most relevant for Equipment Manufacturer persona.

---

## Planned Page Sections

| # | Section | Type | Priority |
|---|---------|------|----------|
| Nav | Navigation bar | Universal | High |
| 01 | Hero + persona toggle | Universal | High |
| 02 | The Problem | Role-specific | High |
| 03 | What QFit Is | Universal | High |
| 04 | How It Works | Universal | High |
| 05 | Use Cases | Role-specific | High |
| 06 | The Science | Role-weighted | Medium |
| 07 | Platform Capabilities | Role-weighted | High |
| 08 | Technology | Role-weighted | Medium |
| 09 | Call to Action | Universal | High |
| 10 | Footer | Universal | Medium |

**Removed from page:**
- Pricing — sales conversation only, not website content
- Market & Traction — investor material, not for general landing page
- Team & Locations — low priority, can be added later

---

## Open Questions (to resolve before Claude Code phase)

| Question | Affects | Priority |
|----------|---------|----------|
| What does "Get started" / "Request a demo" link to? | Nav CTA, Hero, CTA section | High |
| Role-specific Hero graphic? (different app visual per persona vs universal dashboard) | Hero | High |
| Fix tagline length per role causing Hero layout shift | Hero | Medium |
| Do Privacy Policy and Terms pages exist? (GDPR) | Footer | Medium |
| Should team bios / locations be added later? | Optional section | Low |

---

## Design Direction

Fully documented in DESIGN.md.
Summary: Light theme, warm off-white backgrounds, green accents (#4ece7a / #006d36),
Manrope headings + Inter body, Material Symbols icons.
Dark panel used only in Hero app visual (intentional contrast element).

---

## Visual Assets Available

SVG exports from product UI — 24 screens in `source_material/Elements/`:

| Asset group | Best used in |
|-------------|-------------|
| Session Sequencer — Athlete (9 iPad + 1 Garmin) | How it works, Athlete persona |
| Session Sequencer — Trainer (3 screens) | Trainer persona, Platform capabilities |
| Workout Plan Generator (3 screens) | How it works, What QFit Is |
| Analytics — Athlete (3 screens) | Science section, Athlete persona |
| Analytics — Gym population (8 screens) | Gym persona, Operational intelligence |
| Analytics — LLM Integration (2 screens) | LLM communications feature |
| Equipment Library (2 screens) | How it works step 3 |
| Exercise Library (2 screens) | Platform capabilities |

---

## WordPress Handoff Notes

- Clean, well-structured HTML for WordPress conversion
- Tailwind classes documented with CSS equivalents in DESIGN.md
- Avoid JS-heavy interactions where possible
- SVG graphics self-contained (not embedded in JS)
- All text content maintained in CONTENT.md
- Sections independently implementable

---

*Last updated: 2026-04-23 — Page structure updated (role-based toggle confirmed,
pricing/market/team sections removed). Persona problems added. Open questions updated.*
*Original source: QFit_Wireframe_Package_2.html + QFit Overview & Biz Model 03 2025.pdf + QFit_Architecture_Details.pdf*
