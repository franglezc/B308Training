---
name: High-Performance Athletic Dark
colors:
  surface: '#121413'
  surface-dim: '#121413'
  surface-bright: '#383a38'
  surface-container-lowest: '#0d0f0e'
  surface-container-low: '#1a1c1b'
  surface-container: '#1e201f'
  surface-container-high: '#282a29'
  surface-container-highest: '#333534'
  on-surface: '#e2e3e0'
  on-surface-variant: '#c1cab0'
  inverse-surface: '#e2e3e0'
  inverse-on-surface: '#2f3130'
  outline: '#8b947d'
  outline-variant: '#424936'
  surface-tint: '#91db2a'
  primary: '#9ee939'
  on-primary: '#1f3700'
  primary-container: '#84cc16'
  on-primary-container: '#315200'
  inverse-primary: '#416900'
  secondary: '#8bd79b'
  on-secondary: '#003918'
  secondary-container: '#005829'
  on-secondary-container: '#81cc90'
  tertiary: '#a5e837'
  on-tertiary: '#213600'
  tertiary-container: '#8acb12'
  on-tertiary-container: '#345100'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acf847'
  primary-fixed-dim: '#91db2a'
  on-primary-fixed: '#102000'
  on-primary-fixed-variant: '#304f00'
  secondary-fixed: '#a6f4b5'
  secondary-fixed-dim: '#8bd79b'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#005226'
  tertiary-fixed: '#b2f746'
  tertiary-fixed-dim: '#98da27'
  on-tertiary-fixed: '#121f00'
  on-tertiary-fixed-variant: '#334f00'
  background: '#121413'
  on-background: '#e2e3e0'
  surface-variant: '#333534'
typography:
  display-hero:
    fontFamily: Oswald
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: 0.02em
  display-hero-mobile:
    fontFamily: Oswald
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Oswald
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: 0.01em
  headline-lg-mobile:
    fontFamily: Oswald
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0.01em
  headline-md:
    fontFamily: Oswald
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.02em
  headline-sm:
    fontFamily: Oswald
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0.03em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Oswald
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Oswald
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an aggressive, high-performance athletic identity tailored for premium personal training, athletic conditioning, and clinical sports nutrition. Rooted in intense physical discipline and metabolic optimization, the aesthetic blends modern dark mode architecture with high-voltage neon energy. 

The design language synthesizes **High-Contrast Modernism** and **Tactile Athletic Brutalism**:
- Deep carbon and obsidian surfaces provide an uncompromising, focused arena that minimizes visual noise and focuses cognitive energy on metrics, performance, and programming.
- Kinetic neon lime accents deliver an unmistakable electric charge, commanding immediate visual prioritization for progress metrics, primary calls to action, and personal records.
- Heavy sports-display typography creates instant urgency and authoritative weight, countered by razor-sharp utilitarian body sans-serif for crystal-clear readability under fatigue.
- Clean structural container lines, subtle emerald glass backdrops, and focused glow fields project professional athletic rigor.

## Colors

The palette is engineered around dark-adapted environments to convey raw power, precision, and vitality.

### Palette Architecture
- **Primary (`#84CC16` / `#A3E635`):** High-output neon lime. Reserved for high-priority interactive states, primary conversion actions, workout start triggers, active telemetry, and success/PR states. Glow diffusion uses 15–25% alpha layers.
- **Secondary (`#166534` / `#14532D`):** Deep forest green. Operates as structural grounding, container highlights, tinted badges, and gradient ramp anchors that tie back to athletic turf and studio branding.
- **Neutrals (`#0D0F0E`, `#141715`, `#1C201D`):** Deep charcoal and obsidian tones form the layered foundation. Pure black (`#000000`) is avoided in surface cards to preserve edge definition and subtle atmospheric contrast.
- **Text & Accents (`#F8FAFC`, `#94A3B8`, `#475569`):** Pure optical whites provide surgical contrast on primary headlines, while slate-grays delineate metadata, passive labels, and structural dividers.

Use neon lime sparingly: when everything shouts, nothing resonates. Ensure all key data points achieve a minimum contrast ratio of 4.5:1 against their container backdrops.

## Typography

The typographic hierarchy juxtaposes condensed athletic impact with technical precision:

- **Display & Headlines (`Oswald`):** Condensed, sturdy, and high-impact. Render primary action titles, workout module labels, and key performance stats in uppercase with slight positive letter spacing (`0.02em` to `0.08em`) to mirror athletic stadium signage and training logs.
- **Body & Supporting Data (`Inter`):** Clean, objective, and neutral. Carries training instructions, nutritional breakdowns, schedule times, and editorial content without visual distortion or fatigue.
- **Labels & Badges:** Use uppercase `Oswald` for punchy status flags (`ACTIVE`, `PR ACHIEVED`, `NUTRITION PROTOCOL`) to maintain athletic punch even in micro-components.

## Layout & Spacing

The system implements a structured 12-column responsive fluid grid designed for rapid scanning and modular data presentation.

### Breakpoints & Canvas Bounds
- **Mobile (< 768px):** 4-column layout, `margin`: `1rem`, `gutter`: `1rem`. Dense, thumb-accessible layout featuring stacked stat cards and edge-to-edge media blocks.
- **Tablet (768px - 1024px):** 8-column layout, `margin`: `2rem`, `gutter`: `1.25rem`. Balanced dual-column split for training programs alongside nutritional tracking.
- **Desktop (> 1024px):** 12-column layout with a maximum container boundary of `1280px` to maintain strict optical control over wide tracking dashboards and video workout walkthroughs.

Component padding follows a strict 4px/8px incremental scale (`space-xs` through `space-xl`). Dense spatial packing is favored in telemetry cards (heart rate, macros, sets/reps) to keep actionable workout parameters within immediate viewport reach.

## Elevation & Depth

Visual hierarchy is maintained through deep tonal surface staging, hairline structural borders, and electric radial neon blooms.

### Elevation Levels
- **Base Canvas (Level 0):** `#0D0F0E` – Solid grounding, minimal reflectivity.
- **Card Tier 1 (Level 1):** `#141715` with a `1px` subtle outline of `rgba(255, 255, 255, 0.08)` or `rgba(132, 204, 22, 0.15)`. Used for modules, schedule rows, and workout blocks.
- **Interactive Elevated (Level 2):** `#1C201D` with an outer ambient blur: `box-shadow: 0 10px 30px -10px rgba(0, 0, 0, 0.7), 0 0 15px -2px rgba(132, 204, 22, 0.12)`.
- **Neon Accent Glow (Active / Focused):** Dedicated active states project a vivid neon halo using `box-shadow: 0 0 20px rgba(132, 204, 22, 0.35)`.
- **Overlays & Modals (Level 3):** Frosted glass container (`#141715` at 85% opacity with `backdrop-filter: blur(12px)`) framed by a crisp `1px` border of `rgba(132, 204, 22, 0.3)`.

## Shapes

The geometric personality is sharp, technical, and architectural. The default corner radius is soft and compact (`0.25rem` / `4px`), expanding to `0.5rem` (`8px`) on oversized modules and hero feature cards. 

Pill shapes are reserved strictly for high-contrast numeric metric tags, active session pills, and athletic status badges (`rounded-full`). Buttons and input fields retain tight, engineered edges to emphasize discipline, performance speed, and structural precision.

## Components

### Buttons
- **Primary (Action/Enroll):** Solid `#84CC16` fill with bold `#0D0F0E` uppercase typography. On hover, shifts to `#A3E635` with an athletic lime outer glow (`0 0 20px rgba(163, 230, 53, 0.4)`). Active state scales slightly down (`0.98`).
- **Secondary (Program Details):** Dark surface `#141715` with a `1px` perimeter border of `rgba(132, 204, 22, 0.4)` and crisp `#F8FAFC` text. On hover, border transitions to full `#84CC16` with neon lime typography.
- **Ghost/Tertiary:** Transparent background, muted slate-gray text, lime color shift on hover with an underlined kinetic tick mark.

### Cards & Workout Blocks
- Surface set to `#141715` paired with a sharp `1px` border (`rgba(255, 255, 255, 0.08)`).
- Cards support an optional neon left-edge accent line (`3px` solid `#84CC16`) to flag high-priority tasks or active nutritional phases.
- Media headers within cards utilize dark gradient overlays fading into `#141715` to preserve legibility for overlaid stats.

### Chips & Athletic Badges
- **Status Badges:** Compact uppercase tracking badges with background `rgba(22, 101, 52, 0.35)`, border `1px solid rgba(132, 204, 22, 0.4)`, and vibrant `#A3E635` text.
- **Filter Chips:** Solid `#1C201D` with subtle white outline. Selected state transitions to `#84CC16` text with matching glowing border.

### Interactive Tab Navigation
- Horizontal athletic segmented control set inside a `#0D0F0E` container.
- Selected tab features a high-visibility lime under-bar (`2px`) or solid pill fill (`#166534` tint with `#84CC16` outline), driving snappy segment transitions between Training, Nutrition, and Assessment metrics.

### Input Fields & Controls
- Form controls rest on deep charcoal (`#141715`) with a `1px` muted gray-green border.
- Active focus state immediately engages a `1px` solid `#84CC16` perimeter accompanied by a faint `0 0 8px rgba(132, 204, 22, 0.25)` focus glow.
- Checkboxes and toggles employ `#84CC16` check marks and thumb states with dark `#0D0F0E` tracks when active.