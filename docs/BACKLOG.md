# BACKLOG.md - QFit Website Backlog

> All ideas, User Stories and planned sections land here first.
> Nothing gets built without a backlog entry.
> Prioritization happens together between Product Owner and Claude.

---

## Legend

| Status | Meaning |
|--------|---------|
| Idea | Not yet evaluated |
| Ready | Defined and ready to execute |
| In Progress | Currently being worked on |
| Done | Completed and reviewed |
| Rejected | Not going forward (with reason) |

---

## Epic 1: Setup & Infrastructure

| ID | Title | Status | Notes |
|----|-------|--------|-------|
| INF-001 | GitHub repository created | Done | |
| INF-002 | Local development environment set up | Done | |
| INF-003 | Source material added (wireframe, PDFs, SVGs, logos) | Done | |
| INF-004 | Stitch design proposal created | Done | "Precision Performance" |
| INF-005 | Stitch proposal confirmed by PO | Done | Light theme confirmed |
| INF-006 | Design system documented | Done | See DESIGN.md |
| INF-007 | Information architecture defined | Done | Role-based toggle approach — 4 personas |
| INF-008 | Content architecture per persona worked out | Done | All 4 personas fully defined in claude.ai session 2026-04-23 |

---

## Epic 2: Design Prototyping (Claude Design)

> One complete prototype per persona, built section by section in Claude Design.
> Design limit resets Saturday. All briefings are ready in claude.ai chat.

### Persona 1: Gym & Fitness Club

| ID | Section | Status | Notes |
|----|---------|--------|-------|
| DES-GYM-00 | Navigation bar | Done | |
| DES-GYM-01 | Hero + persona toggle (Gym active) | Done | |
| DES-GYM-02 | The Problem (Gym) | Done | |
| DES-GYM-03 | What QFit Is | Done | |
| DES-GYM-04 | How It Works | Done | |
| DES-GYM-05 | Use Cases (Gym tab) | Done | |
| DES-GYM-06 | The Science (Gym-weighted) | Done | |
| DES-GYM-07 | Platform Capabilities (Gym focus) | Done | |
| DES-GYM-08 | Technology (Gym perspective) | Done | |
| DES-GYM-09 | CTA + Footer | Done | |
| DES-GYM-EX | Export as zip / HTML | Done | Exported — ready for review |

### Persona 2: Athletes & Trainers

| ID | Section | Status | Notes |
|----|---------|--------|-------|
| DES-ATH-00 | Navigation bar | Done | |
| DES-ATH-01 | Hero + persona toggle (Athlete active) | Done | |
| DES-ATH-02 | The Problem (Athlete) | Done | |
| DES-ATH-03 | What QFit Is | Ready | Briefing prepared — needs Design session |
| DES-ATH-04 | How It Works | Ready | Briefing prepared |
| DES-ATH-05 | Use Cases (Athlete tab) | Ready | Briefing prepared |
| DES-ATH-06 | The Science (Athlete-weighted) | Ready | Briefing prepared |
| DES-ATH-07 | Platform Capabilities (Athlete focus) | Ready | Briefing to prepare |
| DES-ATH-08 | Technology (Athlete perspective) | Ready | Briefing to prepare |
| DES-ATH-09 | CTA + Footer | Ready | Same as Gym with Athlete copy |
| DES-ATH-EX | Export as zip / HTML | Idea | After sections complete |

### Persona 3: Sports Clubs & Schools

| ID | Section | Status | Notes |
|----|---------|--------|-------|
| DES-CLB-01 | Hero + persona toggle (Club active) | Ready | Briefing to prepare |
| DES-CLB-02 | The Problem (Club) | Ready | Content defined |
| DES-CLB-03 | What QFit Is | Ready | Universal — same base, Club accent |
| DES-CLB-04 | How It Works | Ready | Universal |
| DES-CLB-05 | Use Cases (Club tab) | Ready | Content defined |
| DES-CLB-06 | The Science (Club-weighted) | Ready | WTM + APP + Population Radar |
| DES-CLB-07 | Platform Capabilities (Club focus) | Ready | Analytics + Population |
| DES-CLB-08 | Technology (Club perspective) | Ready | Wearables + data layer |
| DES-CLB-09 | CTA + Footer | Ready | |
| DES-CLB-EX | Export | Idea | |

### Persona 4: Equipment Manufacturers

| ID | Section | Status | Notes |
|----|---------|--------|-------|
| DES-EQP-01 | Hero + persona toggle (Equipment active) | Ready | Briefing to prepare |
| DES-EQP-02 | The Problem (Equipment Mfr.) | Ready | Content defined |
| DES-EQP-03 | What QFit Is | Ready | Universal — Equipment accent |
| DES-EQP-04 | How It Works | Ready | Universal |
| DES-EQP-05 | Use Cases (Equipment tab) | Ready | Content defined |
| DES-EQP-06 | The Science (Equipment-light) | Ready | Brief treatment |
| DES-EQP-07 | Platform Capabilities (Equipment focus) | Ready | API + IMU + Operational |
| DES-EQP-08 | Technology (full depth) | Ready | Architecture + IMU + Partnership |
| DES-EQP-09 | CTA + Footer | Ready | |
| DES-EQP-EX | Export | Idea | |

---

## Epic 3: Design Review & Confirmation

| ID | Title | Status | Notes |
|----|-------|--------|-------|
| REV-001 | Review all 4 prototypes with team | Idea | After all Design exports done |
| REV-002 | Confirm visual direction | Idea | |
| REV-003 | Define interactive / dynamic elements | Idea | Animations, hover states, toggle mechanics |
| REV-004 | Correct tagline length issue per role in Hero | Idea | Known issue — fix after all content final |
| REV-005 | Define role-specific Hero graphics | Idea | Different app visual per persona — bigger decision |

---

## Epic 4: Claude Code Implementation

> Only starts after Epic 3 is complete and design is confirmed.

| ID | Title | Status | Notes |
|----|-------|--------|-------|
| COD-000 | Base HTML scaffold | Idea | From confirmed Design export |
| COD-001 | Navigation bar | Idea | |
| COD-002 | Hero + toggle mechanic (JS) | Idea | Toggle drives all role-specific content |
| COD-003 | The Problem — role-specific | Idea | |
| COD-004 | What QFit Is | Idea | |
| COD-005 | How It Works | Idea | |
| COD-006 | Use Cases — persona tabs | Idea | |
| COD-007 | The Science — role-weighted | Idea | |
| COD-008 | Platform Capabilities — role-weighted | Idea | |
| COD-009 | Technology — role-weighted | Idea | |
| COD-010 | CTA | Idea | |
| COD-011 | Footer | Idea | |
| COD-012 | Integrate real logo SVG | Idea | |
| COD-013 | Integrate product UI SVG screens | Idea | 24 screens available in source_material |
| COD-014 | Interactive elements + animations | Idea | |
| COD-015 | Mobile responsive | Idea | |
| COD-016 | WordPress handoff preparation | Idea | |

---

## Rejected

| ID | Title | Reason |
|----|-------|--------|
| SEC-010 | Pricing section | Removed — pricing is a sales conversation, not website content |
| SEC-011 | Market & traction | Investor material — not for general landing page |

---

## Ideas (not yet evaluated)

- Role-specific Hero graphic (different app visual per persona)
- Animated stepper for How It Works
- Interactive Goal Radar chart
- "Learn more" expandable metric cards in Science section
- Dedicated investors / partners page for market & traction content

---

*Last updated: 2026-04-23 — Restructured for role-based Design approach*
