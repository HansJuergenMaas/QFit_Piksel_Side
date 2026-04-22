# VISION.md — QFit Website

> This document is the north star for all design and content decisions.
> Every section, every headline, every design choice should serve this vision.
> Updated: 2026-04 — filled from wireframe and source material review.

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

The website is built as an HTML + Tailwind CSS prototype that will be handed off to a Piksel colleague for implementation in WordPress on piksel.com. Every design and content decision must account for this handoff.

---

## Core Information Architecture

The website uses a **shared universal entry → persona-specific branching** structure.

### Layer 1 — Universal (everyone sees this)

The opening of the page establishes what QFit is, why it exists, and how it works — in terms that are meaningful regardless of who is reading. This is the shared foundation:

- **Hero** — the tagline, the persona toggle, the first CTA
- **The problem** — the structural problem in the fitness industry
- **What QFit is** — the positioning, the three core descriptors, the key statistics
- **How it works** — the four-step plan generation process
- **The science** — the metrics that make QFit different from any content-based platform

### Layer 2 — Persona branching (each user finds their view)

After the universal foundation, the page branches into a tabbed or navigable use-case section where each persona type sees QFit described in terms of their specific challenges and benefits. This is not a different product — it is the same platform framed through a different lens.

| Persona | Their primary interest | QFit's answer |
|---------|----------------------|---------------|
| **Athlete / Personal trainer** | Performance results, plan quality, session guidance | Individual AI-generated plan, real-time session sequencer, automated feedback reports |
| **Gym / Fitness club owner** | Member retention, trainer scalability, operational data | Churn reduction in first 90 days, personalized coaching without headcount increase, population analytics and equipment utilization data |
| **Sports club / School** | Team conditioning, population testing, injury prevention | Individual plans for every athlete on the squad, VO2max/CMJ/1RM testing protocols, Wear & Tear metric for injury risk |
| **Equipment manufacturer** | Platform integration, data differentiation for hardware | API-first architecture, live session data layer, QFit as the intelligence layer on top of hardware |

### Layer 3 — Platform depth (for those who want more)

After the personas, the remaining sections provide the depth that converts interested visitors into serious leads:

- **Technology** — the architecture, AI engine, integrations (Garmin, Apple, VALD, VO2Master, Catapult), IMU as extended capability
- **Pricing** — gym-size-based tiered subscription model
- **Market & traction** — go-to-market roadmap (Italy launch, 3-stage expansion)
- **Team & locations** — Frankfurt (EU HQ) + Boston (US)
- **Call to action** — final conversion section, mirrors the hero
- **Footer** — navigation, legal, contact

---

## Target Audience — Personas in Detail

### Persona 1: The Athlete / Personal Trainer
*Individual performance focus*

An athlete wants a plan that actually fits them — not a generic 12-week program. They want to know their training is moving the needle toward their specific goals (strength, hypertrophy, power, endurance, mobility — 11 goal types supported). They want session guidance they can follow in the gym, feedback that tells them how the workout actually went, and a program that adapts when things change.

A personal trainer wants to deliver that level of quality to every client without spending hours building programs and spreadsheets. They want automation to handle the reporting and leave them free to actually coach.

**Key message:** *QFit builds your training plan around your body, your goals, and your available time — then tracks every session with the metrics that actually matter. No guesswork. No generic programs. Just measurable progress, every workout.*

### Persona 2: The Gym / Fitness Club Owner
*Scale and retention focus*

A gym owner's problem is the gap between the diverse membership they have and the personalized coaching those members expect. They can't hire enough trainers to close it. The result is churn — most prominently in the first 90–120 days. They also lack data: they don't know what's working, which equipment is being used, or whether their members are progressing.

**Key message:** *QFit is the training intelligence layer that closes the gap between your diverse membership and the personalized coaching they expect — without scaling your trainer headcount.*

The gym deployment model follows a four-stage path: Pilot → Validate → Expand → Full deployment. This gives operators a low-risk entry point.

### Persona 3: The Sports Club / School
*Team conditioning and testing focus*

A sports club director or strength and conditioning coach has a squad of athletes with vastly different physical profiles. They need individual conditioning plans for each, the ability to run population-level assessments (VO2max, CMJ, 1RM), and early warning of injury risk before it becomes a problem.

**Key message:** *Individual conditioning plans for every athlete on your squad. Population analytics for the whole team. Injury risk flagging before it becomes a problem.*

### Persona 4: The Equipment Manufacturer
*Integration and differentiation focus*

A fitness equipment manufacturer wants their hardware to be smarter. QFit's API-first architecture means it can sit as an intelligence layer on top of any equipment ecosystem — capturing real-time session data, enriching it with biomechanical metrics, and feeding it back to athletes and operators. This turns hardware into a platform.

**Key message:** *API-first design means QFit connects to your existing ecosystem — member apps, CRMs, booking systems, wearables — without disruption. No rip-and-replace. Works alongside what you already have.*

---

## Key Messages (across all personas)

These messages are confirmed, sourced from multiple decks, and should be treated as fixed:

| Message | Usage |
|---------|-------|
| "Better workouts. Guaranteed." | Hero tagline — the anchor of the entire page |
| "QFit is not content. It is training intelligence." | Positioning — opens section 03 |
| "From goals to gains — four steps." | How it works headline |
| "Workout planning is no longer an art. It's a science." | The science section headline |
| "Every tool a trainer needs. Every insight an athlete deserves." | Platform capabilities section headline |
| "Built on real biomechanics. Powered by AI." | Technology section headline |
| "Ready to make your workouts better — guaranteed?" | CTA section — bookends the hero |

---

## Key Statistics (confirmed, sourced from Jan 2026 + March 2025 decks)

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

QFit tracks metrics that traditional training tools don't calculate. These are a core differentiator and should be presented on the website in accessible (not academic) language:

| Metric | What it measures |
|--------|----------------|
| **MEE** | Mechanical Energy — total work in kcal, accounts for movement distance and body geometry |
| **F×TuT** | Force × Time under Tension — primary driver of hypertrophy and strength adaptation |
| **MEP** | Metabolic Efficiency — tracks adaptation over time |
| **APP** | Average Peak Power — critical for power-sport athletes |
| **ARV** | Average Rep Velocity — zone-based training prescription |
| **WTM** | Wear & Tear Metric — cumulative joint load, injury prevention signal |
| **WEM** | Workout Efficiency Metric — TuT ratio, time optimization |
| **Goal radar** | Visual match score between current plan and athlete's goals |

---

## Technology Overview

**Architecture:** Inputs → QFit AI (Qi) → Outputs

Inputs: athlete metadata, equipment library, exercise library (2,000+), third-party wearable data

Outputs: workout plan, session sequencer, analytics & reporting, LLM-generated communications

**Integration partners (confirmed):** Garmin, Apple, VALD, VO2Master, Catapult, plus open API

**IMU:** Extended capability — precision motion capture for velocity, acceleration, joint angles, and power during live sessions. Treated as a subtle "technology inside" footnote, not a primary feature.

---

## Planned Page Sections

| # | Section | Priority | Persona relevance |
|---|---------|----------|------------------|
| Nav | Navigation bar | High | All |
| 01 | Hero | High | All |
| 02 | The problem | High | All |
| 03 | What QFit is | High | All |
| 04 | How it works | High | All |
| 05 | The science | Medium | Athletes, Trainers, Clubs |
| 06 | Platform capabilities | High | All |
| 07 | Use cases (persona tabs) | High | Branching point |
| 08 | Technology | Medium | Gyms, Equipment mfr., Tech-savvy |
| 09 | Pricing | Medium | Gyms, Clubs |
| 10 | Market & traction | Low | Investors, Partners |
| 11 | Team & locations | Low | All |
| 12 | Call to action | High | All |
| 13 | Footer | Medium | All |

---

## Open Questions (to resolve before build)

These flags were identified in the wireframe and need answers before development of the affected sections:

| Question | Affects | Priority |
|----------|---------|----------|
| What does "Get started" / "Request a demo" link to? | Nav CTA, Hero CTA, CTA section | High |
| Should the hero sub-headline adapt per persona toggle, or use one universal line? | Hero | High |
| Show pricing in EUR or USD? (Italy launch market) | Pricing | High |
| Are the March 2025 pricing tiers ($30–$500/mo) still current? | Pricing | High |
| Should market/traction data live on the main page or a separate investors page? | Section 10 | Medium |
| Should team bios and photos be included? | Team section | Medium |
| Are the three open roles (trainers, web dev, AWS dev) still current? | Team section | Medium |
| Do Privacy Policy and Terms pages exist (needed for GDPR compliance)? | Footer | Medium |

---

## Design Direction

*Formal design to be developed in a Google Stitch session and documented in DESIGN.md.*
*The notes below are confirmed inputs to that session — not final decisions.*

### Logo & Brand Asset

Three logo files are available in `source_material/`:

| File | Format | Use case |
|------|--------|----------|
| `Logo_long_Qfit.svg` | SVG — horizontal layout | Navigation bar, footer, wide contexts |
| `Logo_short_QFIT.svg` | SVG — compact/square layout | Favicon, icon contexts, mobile nav |
| `Q_fit_grey.png` | PNG | Fallback / reference |

The logo consists of:
- A stylised **Q** mark in a teal-to-lime gradient (speech bubble shape with a pointed lower-left notch)
- The wordmark **"Fit."** — clean, slightly condensed, bold italic letterforms
- Small gradient accent on the period of "Fit."

**Exact gradient colors from SVG source:**
- Start: `#49bcab` (teal-mint)
- End: `#c6fb81` (lime yellow-green)
- Direction: upper-left to lower-right (diagonal)

**Important — light background note:** The SVG files have the "Fit." wordmark in `fill="#fff"` (white), making them optimised for dark backgrounds. For the light-design website, the wordmark fill needs to be changed to dark grey (e.g. `#2d2d2d`) in the SVG. This is a one-line change. Until that is done, use `Q_fit_grey.png` as the light-background reference.

### Colour Direction — Bright, Not Dark

The QFit website should use a **bright, light design** — white or near-white backgrounds with the brand green as the primary accent. This is a deliberate departure from the dark wireframe aesthetic, which was a design tool document rather than a brand statement.

Rationale:
- The QFit logo reads best on light backgrounds
- A bright design reads as professional, accessible, and trustworthy — appropriate for the B2B gym/club audience as well as individual athletes
- Consistency with the Piksel parent brand (piksel.com uses a light design)
- The existing SVG app screenshots have their own dark UI — these will stand out as product visuals against a light page background

**Colour palette direction (to refine in Stitch):**

| Role | Direction | Note |
|------|-----------|------|
| Background | White `#ffffff` / very light grey `#f8f9fa` | Clean, open |
| Primary accent | Lime-green `#c6fb81` (gradient end, logo) | Buttons, highlights, active states |
| Secondary accent | Teal-mint `#49bcab` (gradient start, logo) | Gradient use, hover states, icons |
| Body text | Dark grey `#1a1a1a` or `#222222` | Not pure black — softer |
| Secondary text | Medium grey `#6b7280` | Subheadings, captions, metadata |
| Borders / dividers | Light grey `#e5e7eb` | Subtle structure |
| Card backgrounds | `#f3f4f6` | Feature cards, stat blocks |

The green-to-teal gradient from the Q mark can be used as a design motif — for CTA buttons, section accents, or decorative elements — keeping the logo's energy throughout the page.

### Typography — Aligned with Piksel Brand

Fonts are taken directly from the Piksel website (piksel.com), identified from the source document:

| Font | Role | Weights used |
|------|------|-------------|
| **Manrope** | Display / headings | Regular (400), Medium (500) |
| **Inter** | Body text / UI / labels | Regular (400), Medium (500), Bold (700) |

Both fonts are available on Google Fonts. Manrope has a distinctive warmth and character that suits the QFit brand's aspiration to feel both scientific and human. Inter is excellent for readability at small sizes — ideal for metric labels, captions, and body copy.

```css
/* Google Fonts import */
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&family=Inter:wght@400;500;700&display=swap');
```

### Tone & Feel

- **Professional, not clinical.** The science is real — but the page should feel confident and human, not like a technical whitepaper.
- **Data-forward.** Charts, metrics, and app screenshots are visual heroes. Feature cards with numbers and metrics should be prominent.
- **Not "wellness soft".** No soft pastels, no stock-photo gym imagery. The product is a precision tool.
- **Not startup-loud.** No aggressive gradient backgrounds, no oversized emoji, no "🚀 Join the revolution" energy.

The visual reference point is a well-designed B2B SaaS product page — think Notion, Linear, or Vercel — but with the warmth of the green brand colour and the credibility of real biomechanics data as visual proof.

### Visual Assets Available

SVG exports from the product UI, ready for use on the page:

| Asset group | Files | Best used in |
|-------------|-------|-------------|
| Session Sequencer — Athlete | 9 iPad screens + 1 Garmin | How it works, Athlete persona section |
| Session Sequencer — Trainer | 3 screens | Trainer persona section, Platform capabilities |
| Workout Plan Generator | 3 screens | How it works, What QFit is |
| Analytics — Athlete | 3 screens | The science, Athlete persona |
| Analytics — Gym population | 8 screens | Gym persona section, Operational intelligence |
| Analytics — LLM Integration | 2 screens | LLM communications feature |
| Equipment Library | 2 screens | How it works (equipment step) |
| Exercise Library | 2 screens | Platform capabilities |
| Landing page mockups | 1 SVG + 1 PNG | Reference / hero section |

---

## WordPress Handoff Notes

- All HTML/CSS must be clean and well-structured for WordPress conversion
- Tailwind classes should be documented with CSS equivalents in DESIGN.md
- Avoid JavaScript-heavy interactions that are hard to replicate in WordPress
- SVG graphics should be self-contained files (not embedded in JS)
- All text content maintained separately in CONTENT.md
- Sections should be self-contained and independently implementable

---

*Last updated: 2026-04 — written from wireframe package and source material review*
*Source: QFit_Wireframe_Package_2.html + QFit Overview & Biz Model 03 2025.pdf + QFit_Architecture_Details.pdf*
