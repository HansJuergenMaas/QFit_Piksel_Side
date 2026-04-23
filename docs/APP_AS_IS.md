# APP_AS_IS.md - QFit Website: Current State

> This document describes the actual, implemented state of all deliverables.
> Updated at the end of every session.
> This is not a wishlist — only what actually exists and works.

---

## Status Overview

**Version:** 0.3.0
**Last updated:** 2026-04-23
**Current phase:** Design Prototyping (Claude Design)

---

## Repository

| Component | Status | Details |
|-----------|--------|---------|
| GitHub Repository | Active | github.com/HansJuergenMaas/Qfit_Piksel_Side |
| Local development folder | Active | ~/Documents/My-Projects/WebSite/QFit_Piksel_Side |

---

## Source Material (in source_material/)

| Material | Format | Status |
|----------|--------|--------|
| QFit_Wireframe_Package_2.html | HTML | In repo — full 14-section wireframe with draft copy |
| QFit Overview & Biz Model 03 2025.pdf | PDF | In repo — March 2025 overview deck |
| QFit_Architecture_Details.pdf | PDF | In repo — architecture details deck |
| Logo_long_Qfit.svg | SVG | In repo — horizontal logo |
| Logo_short_QFIT.svg | SVG | In repo — compact logo mark |
| Q_fit_grey.png | PNG | In repo — light-background logo reference |
| Piksel_Web_Page_Fonts | PDF | In repo — confirms Manrope + Inter |
| Elements/ (SVG exports) | SVG | In repo — 24 product UI screens across 6 categories |
| stitch_qfit_marketing_platform_website/ | HTML + MD + PNG | In repo — Stitch design proposal (confirmed) |

---

## Information Architecture

| Item | Status | Details |
|------|--------|---------|
| Role-based toggle approach | Confirmed | 4 personas drive all content |
| Persona 1: Athletes & Trainers | Defined | Full content architecture ready |
| Persona 2: Gyms & Fitness Clubs | Defined | Full content architecture ready |
| Persona 3: Sports Clubs & Schools | Defined | Full content architecture ready |
| Persona 4: Equipment Manufacturers | Defined | Full content architecture ready |
| Pricing section | Rejected | Removed — sales conversation only |
| Market & traction section | Rejected | Investor material — not for landing page |

---

## Design System

| Item | Status | Details |
|------|--------|---------|
| Theme | Confirmed | "Precision Performance" — light theme |
| Background | Confirmed | #fcf9f8 (warm off-white) |
| Primary color | Confirmed | #006d36 / #4ece7a |
| Gradient | Confirmed | #6be87a → #3dd9a4 |
| Fonts | Confirmed | Manrope (headings) + Inter (body) |
| Icons | Confirmed | Material Symbols Outlined |
| Cards | Confirmed | bg #f3f4f6, border #e5e7eb, hover #4ece7a |
| Hero app visual | Confirmed | Dark panel #313030 inside light page |
| Stitch code.html | In repo | Base reference — design system source |

---

## Claude Design Prototypes

### Persona 2: Gym & Fitness Club

| Section | Status | Notes |
|---------|--------|-------|
| Navigation bar | Complete | |
| Hero + persona toggle | Complete | Gym active |
| The Problem | Complete | 4 cards: scale / churn / visibility / comms |
| What QFit Is | Complete | Blockquote + 3 columns + stats row |
| How It Works | Complete | 4-step stepper + detail cards |
| Use Cases (Gym tab) | Complete | Left copy + deployment flow + metric cards |
| The Science | Complete | 4 metrics: WTM / MEE / F×TuT / Goal Radar |
| Platform Capabilities | Complete | 3 primary + 2 secondary feature cards |
| Technology | Complete | Architecture diagram + integration badges |
| CTA + Footer | Complete | |
| **Export** | **Complete** | Exported as zip (React/JSX + HTML) |

### Persona 1: Athletes & Trainers

| Section | Status | Notes |
|---------|--------|-------|
| Navigation bar | Complete | |
| Hero + persona toggle | Complete | Athlete active |
| The Problem | Complete | 4 cards: generic / no feedback / injury / scale |
| What QFit Is | Not started | Briefing ready |
| How It Works | Not started | Briefing ready |
| Use Cases (Athlete tab) | Not started | Briefing ready |
| The Science | Not started | Briefing ready |
| Platform Capabilities | Not started | Briefing to prepare |
| Technology | Not started | Briefing to prepare |
| CTA + Footer | Not started | |
| Export | Not started | |

### Persona 3: Sports Clubs & Schools

| Section | Status | Notes |
|---------|--------|-------|
| All sections | Not started | Content defined — briefings to prepare |

### Persona 4: Equipment Manufacturers

| Section | Status | Notes |
|---------|--------|-------|
| All sections | Not started | Content defined — briefings to prepare |

---

## index.html (Claude Code)

| Status | Details |
|--------|---------|
| Not started | Awaiting design confirmation after all prototypes reviewed |

---

## Tech Stack

| Layer | Technology | Status |
|-------|------------|--------|
| Prototyping | Claude Design (React/JSX) | Active — in progress |
| Frontend | HTML + Tailwind CSS | Planned — starts after design confirmed |
| Fonts | Manrope + Inter (Google Fonts) | Confirmed |
| Graphics | SVG (24 product UI screens) | Available in source_material |
| Version control | GitHub | Active |

---

## Known Issues / Open Decisions

| Issue | Notes |
|-------|-------|
| Tagline length per role | Sub-headlines have different lengths causing layout shift — fix after all content final |
| Role-specific Hero graphic | Decision pending: universal dashboard vs. role-specific app visual |
| Design usage limit | Reached 100% on 2026-04-23 — resets Saturday |
| Download button in Design | Not working reliably — use zip export via prompt instead |

---

## Changelog

| Version | Date | What changed |
|---------|------|-------------|
| 0.0.0 | 2026-04 | Project started |
| 0.1.0 | 2026-04-22 | All source material added. VISION.md completed. Design system defined. Stitch proposal received. |
| 0.2.0 | 2026-04-23 | Role-based information architecture defined. Content for all 4 personas worked out. Design system confirmed (light theme). |
| 0.3.0 | 2026-04-23 | Gym & Fitness Club prototype complete and exported. Athlete & Trainer prototype started (Hero + Problem). Design usage limit reached. |

---

*This document is updated at the end of every session.*
