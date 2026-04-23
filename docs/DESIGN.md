# DESIGN.md - QFit Website Design System

> This document is the single source of truth for all design decisions.
> Every visual choice in Claude Design and Claude Code must follow these rules.
> Updated: 2026-04-23 — confirmed from Stitch proposal (code.html).

---

## Design Direction — "Precision Performance" (Light)

**Theme:** Light — warm off-white backgrounds, green accents, dark text.
**Tone:** Professional, data-forward, scientific but human. Not clinical, not startup-loud.
**Reference:** Well-designed B2B SaaS (Notion, Linear, Vercel) — with QFit's green energy.

The dark wireframe aesthetic was a design tool document, not a brand statement.
The confirmed direction is light — consistent with the Piksel parent brand.

---

## Colors

### Backgrounds & Surfaces

| Token | Value | Usage |
|-------|-------|-------|
| Page background | `#fcf9f8` | Warm off-white — primary page bg |
| Section alt 1 | `#f6f3f2` | Problem, Science, Technology sections |
| Section alt 2 | `#f0eded` | CTA section container |
| White | `#ffffff` | What QFit Is, How It Works, Capabilities |
| Card background | `#f3f4f6` | Bento cards, feature cards |
| Stats row bg | `rgba(78,206,122,0.05)` | Very subtle green tint for stat blocks |

### Brand Colors

| Token | Value | Usage |
|-------|-------|-------|
| Primary | `#006d36` | Text on light, icons, active states |
| Primary container | `#4ece7a` | Buttons, highlights, active borders |
| Gradient start | `#6be87a` | Logo, glow effects, gradient text |
| Gradient end | `#3dd9a4` | Logo, glow effects, gradient text |
| Secondary | `#006c4e` | Supporting green tones |
| Secondary container | `#68fcc4` | Subtle green fills |

### Text Colors

| Token | Value | Usage |
|-------|-------|-------|
| Body text | `#1c1b1b` | Primary text — not pure black |
| Muted text | `#3d4a3f` | Secondary text, descriptions |
| Placeholder / meta | `#6d7a6e` | Captions, labels, icon color |
| Light text | `#6b7280` | Footer links, small metadata |

### Borders

| Token | Value | Usage |
|-------|-------|-------|
| Default border | `#e5e7eb` | Cards, dividers |
| Subtle border | `#bccabb` | Ghost buttons, inactive elements |
| Accent border | `#4ece7a` | Hover states, active cards, blockquote |

### Special: Hero Dark Panel

The hero right column uses a dark panel inside the light page — intentional contrast.

| Token | Value | Usage |
|-------|-------|-------|
| Dark panel bg | `#313030` | Hero app visual container |
| Dark panel border | `rgba(255,255,255,0.10)` | Subtle edge |
| Panel glow | gradient `#4ece7a → #68fcc4` | Blur opacity-20 behind dark panel |
| Data accent on dark | `#4ece7a` | Metric numbers, chart bars on dark bg |

---

## Typography

### Fonts

```css
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@600;700;800&family=Inter:wght@400;500;600&display=swap');
```

| Font | Role | Weights |
|------|------|---------|
| **Manrope** | Headings, display, buttons, tabs | 600, 700, 800 |
| **Inter** | Body, labels, captions, metadata | 400, 500, 600 |

### Type Scale

| Token | Font | Size | Line height | Letter spacing | Weight |
|-------|------|------|-------------|----------------|--------|
| display-lg | Manrope | 48px | 1.1 | -0.02em | 800 |
| h1 | Manrope | 32px | 1.2 | -0.01em | 700 |
| h2 | Manrope | 24px | 1.3 | 0 | 600 |
| h3 | Manrope | 20px | 1.4 | 0 | 600 |
| body-lg | Inter | 18px | 1.6 | 0 | 400 |
| body-md | Inter | 16px | 1.5 | 0 | 400 |
| body-sm | Inter | 14px | 1.5 | 0 | 400 |
| label-caps | Inter | 12px | 1.0 | 0.05em | 600 |
| metric-xl | Inter | 40px | 1.0 | -0.03em | 700 |

### Special Treatments

- **Gradient text** (headline accent): `background: linear-gradient(#6be87a, #3dd9a4); -webkit-background-clip: text`
- **Blockquote**: Manrope italic, H1 size, left border 8px `#4ece7a`
- **Eyebrow / badge**: label-caps style, color `#006d36`, uppercase

---

## Spacing

| Token | Value | Usage |
|-------|-------|-------|
| xl | 64px | Section vertical padding |
| lg | 40px | Component gaps, section horizontal padding |
| md | 24px | Card internal padding, grid gaps |
| sm | 16px | Small gaps |
| xs | 8px | Tight gaps |

---

## Border Radius

| Token | Value | Usage |
|-------|-------|-------|
| Default | 4px | Small elements |
| lg | 8px | Small cards |
| xl | 12px | Standard cards (rounded-xl) |
| 2xl | 16px | Larger containers |
| 3xl | 24px | Section containers |
| full | 9999px | Buttons (pill), tags, badges |
| section | 40px | CTA container, stats row (rounded-[40px]) |

---

## Components

### Buttons

**Primary:**
```
rounded-full, bg #4ece7a, color #005428
padding: 16px 32px (py-4 px-8)
font: Manrope bold
hover: bg #3dd9a4
shadow: shadow-lg shadow-#4ece7a/20
```

**Secondary (ghost):**
```
rounded-full, bg white, border #bccabb, color #1c1b1b
padding: 16px 32px
font: Manrope bold
hover: bg #f6f3f2
```

**CTA size (larger):**
```
padding: 20px 40px (py-5 px-10)
font-size: 18px
```

### Cards (Bento style)

```
bg: #f3f4f6
border: 1px solid #e5e7eb
border-radius: 12px (rounded-xl)
padding: 24px
transition: border-color 0.3s
hover: border-color #4ece7a
```

**Primary card variant** (highlighted):
```
border-left: 4px solid #006d36
```

### Tags / Badges

```
rounded-full
bg: rgba(78,206,122,0.1)
border: 1px solid #4ece7a
color: #006d36
font: Inter 12px, label-caps
padding: 4px 12px
```

### Integration badges:
```
rounded-full
border: 1px solid #bccabb
bg: white
color: #3d4a3f
font: Inter body-sm
padding: 6px 16px
```

API-first badge: dashed border `#4ece7a`, color `#006d36`

### Persona Toggle (Hero)

```
Container: rounded-full, bg #f6f3f2, border #bccabb, padding 4px
Active pill: bg white, shadow-sm, color #006d36, Manrope semibold
Inactive pill: color #3d4a3f, hover bg white/50
Font: Manrope semibold, 14px
```

### Stats Row

```
bg: rgba(78,206,122,0.05)
border-radius: 40px
padding: 48px
layout: 4-column grid
number: metric-xl style, color #006d36
label: label-caps, color #3d4a3f, margin-top 8px
```

### Blockquote

```
border-left: 8px solid #4ece7a
padding-left: 40px
padding-top: 16px, padding-bottom: 16px
font: Manrope italic, H1 size
color: #1c1b1b
max-width: 3xl
```

---

## Icons

**Library:** Material Symbols Outlined (Google)
**Default weight:** 400
**Primary color:** `#006d36`
**Muted color:** `#6d7a6e`
**Size:** 24px standard, 32px for feature cards

```html
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet"/>
```

---

## Logo

Three files available in `source_material/`:

| File | Use case |
|------|----------|
| `Logo_long_Qfit.svg` | Navigation, footer, wide contexts |
| `Logo_short_QFIT.svg` | Favicon, icon contexts, mobile |
| `Q_fit_grey.png` | Light background reference |

**Logo gradient colors (from SVG source):**
- Start: `#49bcab` (teal-mint)
- End: `#c6fb81` (lime yellow-green)

**Important:** SVG wordmark fill is `#fff` (white) — optimized for dark backgrounds.
For light background use: change fill to `#2d2d2d` or use `Q_fit_grey.png`.

**Stitch approximation used in prototypes:**
- Icon: gradient `#6be87a → #3dd9a4`, rounded square, white Q inside bold italic
- Wordmark: "Fit." Manrope bold #1c1b1b

---

## Navigation Bar

```
bg: white (#ffffff), backdrop-blur-md
border-bottom: 1px solid #f3f4f6
height: 80px
padding: horizontal 40px
max-width: 7xl, centered
position: sticky top-0, z-50

Left: Logo
Center: Links — Manrope semibold 14px, #4b5563, hover emerald-500
Right: "Get started" — primary button (smaller: px-6 py-2.5)
```

---

## Section Backgrounds (alternating rhythm)

| Section | Background |
|---------|------------|
| Navigation | `#ffffff` |
| Hero | `#fcf9f8` |
| The Problem | `#f6f3f2` |
| What QFit Is | `#ffffff` |
| How It Works | `#ffffff` |
| Use Cases | `#fcf9f8` |
| The Science | `#f6f3f2` |
| Platform Capabilities | `#ffffff` |
| Technology | `#f6f3f2` |
| CTA | `#f0eded` rounded-[40px] |
| Footer | `#f9fafb` |

---

## SVG Product Assets

Available in `source_material/Elements/` — 24 screens across 6 categories:

| Group | Files | Best used in |
|-------|-------|-------------|
| Session Sequencer — Athlete | 9 iPad + 1 Garmin | How it works, Athlete persona |
| Session Sequencer — Trainer | 3 screens | Trainer persona, Platform capabilities |
| Workout Plan Generator | 3 screens | How it works, What QFit Is |
| Analytics — Athlete | 3 screens | Science section, Athlete persona |
| Analytics — Gym population | 8 screens | Gym persona, Operational intelligence |
| Analytics — LLM Integration | 2 screens | LLM communications feature |
| Equipment Library | 2 screens | How it works step 3 |
| Exercise Library | 2 screens | Platform capabilities |

These replace the designed placeholder visuals in Claude Design prototypes
when Claude Code implements the final HTML.

---

## WordPress Handoff Notes

- Document all Tailwind classes with CSS equivalents
- Avoid JS-heavy interactions — prefer CSS transitions
- SVG files must be self-contained (not embedded in JS bundles)
- All text content maintained separately in CONTENT.md
- Sections must be independently implementable

---

*Last updated: 2026-04-23 — Confirmed from Stitch proposal (code.html) and Design session*
