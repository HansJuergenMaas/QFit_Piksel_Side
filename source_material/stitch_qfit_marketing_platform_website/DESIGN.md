---
name: Precision Performance
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#3d4a3f'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#6d7a6e'
  outline-variant: '#bccabb'
  surface-tint: '#006d36'
  primary: '#006d36'
  on-primary: '#ffffff'
  primary-container: '#4ece7a'
  on-primary-container: '#005428'
  inverse-primary: '#60de88'
  secondary: '#006c4e'
  on-secondary: '#ffffff'
  secondary-container: '#68fcc4'
  on-secondary-container: '#007353'
  tertiary: '#006e25'
  on-tertiary: '#ffffff'
  tertiary-container: '#51cf65'
  on-tertiary-container: '#00541a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7dfca2'
  primary-fixed-dim: '#60de88'
  on-primary-fixed: '#00210c'
  on-primary-fixed-variant: '#005227'
  secondary-fixed: '#68fcc4'
  secondary-fixed-dim: '#45dfa9'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#00513a'
  tertiary-fixed: '#7ffc8c'
  tertiary-fixed-dim: '#62df72'
  on-tertiary-fixed: '#002106'
  on-tertiary-fixed-variant: '#00531a'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h2:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  metric-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: -0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  margin: 32px
---

## Brand & Style

This design system establishes a high-performance, data-driven environment for AI-assisted fitness training. The brand persona is authoritative yet encouraging—acting as a digital coach that prioritizes clarity, progress tracking, and professional-grade metrics. 

The visual style is **Corporate / Modern**, leaning heavily into a refined B2B SaaS aesthetic. It utilizes a "Functional Minimalism" approach: maximizing whitespace to reduce cognitive load while using vibrant green-to-teal accents to signal action and vitality. The interface should feel light, airy, and hyper-organized, evoking the feeling of a premium clinical or athletic laboratory where data is the primary driver of success.

## Colors

The palette is built on a foundation of "Active Neutrals." Pure white and soft greys provide a sterile, professional canvas that allows data visualizations to take center stage. 

- **Primary & Secondary:** A vibrant duo of Green (#4ece7a) and Teal (#3dd9a4) represent growth and energy. These are reserved for high-intent actions, active states, and critical success metrics.
- **Gradients:** A linear 135° gradient from Lime-green to Teal-green is used sparingly for the brand mark and "hero" data points to imply movement and progression.
- **Typography & UI:** Deep grey (#1a1a1a) ensures maximum legibility for body text, while a cooler grey (#6b7280) handles metadata and supportive labels.

## Typography

The typographic system utilizes a dual-font strategy to balance character with utility. 

- **Manrope** is used for headlines and display text. Its modern, geometric construction provides a refined and trustworthy feel for high-level information architecture.
- **Inter** is the workhorse for the UI. It is used for all body copy, labels, inputs, and—most importantly—metrics. Inter's tall x-height and excellent legibility make it ideal for the dense data tables and performance dashboards common in this design system.
- **Data Emphasis:** For numerical metrics, use "Metric-XL" or "H2" sizes with tight letter spacing to create a sense of urgency and precision.

## Layout & Spacing

This design system employs a **Fixed-Fluid Hybrid Grid**. Content is housed within a 12-column structure with a max-width of 1440px for desktop, centered on the page. 

- **Spacing Rhythm:** Based on a 4px baseline, with standard increments of 8px (xs), 16px (sm), and 24px (md). 
- **Whitespace:** Use generous padding (40px+) between major sections to maintain a clean, "uncluttered" SaaS feel. 
- **Alignment:** All data points within cards should be left-aligned for quick scanning, while primary CTA buttons are typically right-aligned in modals and bottom-aligned in sidebars.

## Elevation & Depth

To maintain a professional B2B aesthetic, depth is achieved through **Low-contrast Outlines** and **Tonal Layers** rather than heavy shadows.

- **Level 0 (Base):** White (#ffffff) background.
- **Level 1 (Cards):** Light grey (#f3f4f6) or white with a 1px border (#e5e7eb).
- **Level 2 (Active/Hover):** Subtlest shadow possible (0px 4px 12px rgba(0,0,0,0.03)) to indicate interactivity.
- **Depth through Color:** Background tiers create hierarchy; use #f8f9fa for sidebars and navigation backgrounds to distinguish them from the primary content canvas.

## Shapes

The shape language is "Softly Geometric." While the overall grid is rigid and professional, individual components use rounded corners to feel accessible and modern.

- **Primary Radius:** 0.5rem (8px) for standard cards, inputs, and containers.
- **Pill Shapes:** Used exclusively for Buttons and Tags/Chips to make them stand out as interactive elements against the rectangular layout.
- **Interactive States:** On hover, rounded elements may transition slightly, but corner radii remain constant to ensure a stable UI.

## Components

- **Logo:** The brand mark consists of a 'Q' speech bubble with a gradient (#6be87a to #3dd9a4). The wordmark "Fit" follows in *Bold Italic* #1a1a1a.
- **Buttons:** Primary buttons are pill-shaped with #4ece7a backgrounds and white text. Secondary buttons use a 1px border of #e5e7eb with #1a1a1a text. Hover states for primary buttons should transition to the Teal (#3dd9a4).
- **Cards:** Use #f3f4f6 for the background. Content should be padded by 24px. Borders should be 1px solid #e5e7eb.
- **Metric Callouts:** Large, bold Inter numbers in #1a1a1a paired with a small 'Label-Caps' descriptor in #6b7280.
- **Input Fields:** 8px rounded corners, white background, 1px #e5e7eb border. On focus, the border changes to #4ece7a.
- **Progress Bars:** Use the Green-to-Teal gradient for the "filled" portion of progress bars, with a light grey #e5e7eb track.
- **AI Insights:** Specialized "Insight" cards should feature a very subtle teal-tinted border to differentiate them from standard training data.