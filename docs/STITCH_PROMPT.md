# Google Stitch Design Prompt — QFit Website

> Copy this prompt into Google Stitch to generate the initial design proposal.
> After reviewing the Stitch output, document the chosen design direction in DESIGN.md.

---

## Prompt

Design a marketing website for **QFit** — an AI-powered fitness training platform by Piksel.

---

### About QFit

QFit is not a fitness content app. It is **training intelligence** — an AI engine built on a real human biomechanics model (200+ bones, 600+ muscles) that generates fully individualized workout programs, sequences live training sessions, tracks performance against precise physiological metrics, and scales personalized coaching from one athlete to 100,000 gym members automatically.

**Tagline:** "Better workouts. Guaranteed."
**Positioning:** "QFit is not content. It is training intelligence."

The platform serves four distinct audiences: individual athletes and personal trainers, gym and fitness club operators, sports clubs and schools, and fitness equipment manufacturers.

---

### Design Requirements

**Overall aesthetic:**
- **Bright, light design** — white or near-white backgrounds (#ffffff / #f8f9fa). Not dark.
- Professional, confident, data-forward. Think: a well-designed B2B SaaS product page.
- Not "wellness soft" (no pastels, no stock gym photography). Not startup-loud (no heavy gradients, no oversized type).
- The product is a precision tool used by coaches, gym operators, and athletes who care about results.

**Logo:**
- The QFit logo consists of a teal-to-lime gradient Q mark (speech bubble shape with a pointed lower-left notch) alongside the wordmark "Fit." in bold italic.
- Exact gradient: `#49bcab` (teal-mint, start) → `#c6fb81` (lime yellow-green, end), running diagonally upper-left to lower-right.
- Two SVG files are available: `Logo_long_Qfit.svg` (horizontal) and `Logo_short_QFIT.svg` (compact). The wordmark will be rendered in dark grey on the light-background version.
- The logo must appear clearly in the navigation bar and footer on a light background.

**Colour palette:**
- Background: white `#ffffff` and light grey `#f8f9fa`
- Primary accent (lime): `#c6fb81` — buttons, highlights, active states, section accents
- Secondary accent (teal): `#49bcab` — gradient use, hover states, decorative elements, icons
- The teal-to-lime gradient from the logo can be used as a repeating design motif (CTA buttons, section borders, graphic accents)
- Body text: dark grey `#1a1a1a`
- Secondary text / captions: `#6b7280`
- Card backgrounds: `#f3f4f6`
- Borders: `#e5e7eb`

**Typography:**
- **Manrope** — display font for headlines and section headers (weights: 400, 500, 600, 700). Available on Google Fonts.
- **Inter** — body text, UI labels, captions, metric values (weights: 400, 500, 700). Available on Google Fonts.
- Headline style: large, confident, with generous line height. Not condensed. Not all-caps.
- Body text: comfortable reading size (16–18px), neutral, clear.

---

### Page Structure to Design

The page has a **universal shared entry layer** followed by **persona-specific branching sections**. Please design the following sections:

#### 1. Navigation bar (sticky)
- Logo left, nav links centre, "Get started" CTA button right
- Nav links: How it works / Features / Use cases / Pricing / About
- CTA button: green accent, pill or rounded rectangle shape
- Clean white background, subtle bottom border on scroll

#### 2. Hero section
- Left: headline + sub-headline + persona toggle pills (Athlete / Trainer / Gym / Club) + two CTA buttons ("Get started" primary green, "See how it works" secondary outline)
- Right: a data dashboard / app analytics mockup (dark UI card on a light background — creates contrast)
- Headline: **"Better workouts. Guaranteed."** — large, bold, Manrope
- Eyebrow label above headline: "Digital Gym Application" — small, green, uppercase
- The persona toggle pills change the sub-headline text dynamically

#### 3. The problem section
- Section headline: "The gym industry has a fundamental problem."
- 2×2 grid of problem cards with short titles and descriptions
- Cards: light grey background, subtle border, clean typography
- Problems: Generic training / Trainers don't scale / High early churn / No operational visibility

#### 4. What QFit is
- Featured quote block: "QFit is not content. It is training intelligence." — visually distinct, green left border or accent
- 3-column feature grid below: Intelligence layer / Goal-focused / Automated & scalable
- Row of 4 stat callouts: 2,000+ exercises / 11 athletic goals / 600+ muscles modelled / 17 onboarding steps
- Stats should use large numbers in the green accent colour

#### 5. How it works
- Section headline: "From goals to gains — four steps."
- Horizontal stepper: Step 1 Athlete assessment → Step 2 Goals & time → Step 3 Equipment → Step 4 AI-generated plan
- Step 4 should be highlighted with the green accent (this is the payoff)
- Below: expandable detail cards for each step

#### 6. Platform capabilities
- Section headline: "Every tool a trainer needs. Every insight an athlete deserves."
- 2×3 grid of feature cards: Program generation / Session sequencer / Auto-adaptation / Analytics / LLM communications / Operational intelligence
- Cards with icon + title + short description
- Consider using the green accent for one highlighted "hero" card

#### 7. Use cases / Personas
- Tabbed section with 4 tabs: Athletes & trainers / Gyms & fitness clubs / Sports clubs & schools / Equipment manufacturers
- Each tab: left panel (badge + headline + description + benefit bullets + CTA) / right panel (metrics/stats + visual element)
- Tabs should feel like switching context, not just changing text

#### 8. Call to action
- Full-width section, slightly darker or coloured background (could use a very subtle green tint or light grey)
- Centred: headline + sub-line + two buttons (Get started / Request a demo)
- Headline: "Ready to make your workouts better — guaranteed?"
- Mirrors the hero section for visual bookending

#### 9. Footer
- Logo + contact email (contact@qfit.ai) + nav links + legal links
- Clean, minimal, white or very light grey background

---

### Visual Language Notes

- **Product UI screenshots** will be placed on the page as dark-UI cards or device mockups against the light background. These create natural contrast and visual interest without the page itself needing to be dark.
- **Data and metrics** are visual heroes. Large numbers, stat callouts, and chart previews should feel prominent and credible.
- **Cards** should use subtle shadows or borders rather than heavy outlines. Keep them light and airy.
- **Green accent** should be used sparingly but consistently — buttons, key highlights, active states, the occasional section border or divider. Not overused.
- **Spacing** should be generous. The page should breathe. Not cluttered.
- **Mobile-first thinking** — all sections should work equally well on mobile. The persona tabs may stack vertically on mobile.

---

### Reference aesthetic

The design should feel like a considered combination of:
- **Linear.app** — clean, precise, data-forward, confident typography
- **Notion.so** — bright, open, generous whitespace
- With the warmth of the **QFit green gradient** as the distinctive brand element

---

*Generated: 2026-04 | For: QFit website v1.0 | Tool: Google Stitch*
