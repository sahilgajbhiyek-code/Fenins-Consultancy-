---
name: Institutional Redefined
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5e3f3a'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#936e68'
  outline-variant: '#e8bcb5'
  surface-tint: '#c00000'
  primary: '#a50000'
  on-primary: '#ffffff'
  primary-container: '#d30000'
  on-primary-container: '#ffe2dd'
  inverse-primary: '#ffb4a8'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#4e5050'
  on-tertiary: '#ffffff'
  tertiary-container: '#676868'
  on-tertiary-container: '#e8e8e8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#930000'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.15em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

The design system is a high-end corporate-editorial hybrid designed for elite management consultancy. It evokes institutional stability, intellectual rigor, and premium exclusivity. By pairing a high-contrast serif with a functional sans-serif, the system balances traditional authority with modern clarity.

The visual style is characterized by **Razor-Sharp Minimalism**. It utilizes stark white space, precise geometric alignment, and a dramatic "Power Red" to direct focus. The aesthetic avoids all decorative ornamentation in favor of structural integrity—using hairline dividers and grid-based layouts to convey a sense of meticulous attention to detail. The target audience is C-suite executives who value efficiency, discretion, and definitive expertise.

## Colors

This design system employs a restricted, high-impact palette to maintain institutional gravitas.

- **Primary (Crimson):** Used sparingly as a "surgical" accent for critical calls to action, active states, and editorial highlights. It represents the "Fenins" signature of quality.
- **Secondary (Pure Black):** The foundation for all typography and structural lines. It provides the heavy contrast required for a premium feel.
- **Backgrounds:** A hierarchy of white is used. Pure white (#FFFFFF) is the primary canvas, while Soft Off-White (#FAFAFA) is used for subtle section differentiation without breaking the clean aesthetic.
- **Dividers:** Thin Gray (#E5E5E5) is used for low-priority structural separation, ensuring the grid is visible but never overwhelming.

## Typography

The typographic hierarchy is built on a high-contrast relationship between **Playfair Display** (for narrative and leadership) and **Inter** (for data and utility).

- **Headlines:** Set in Playfair Display with tight letter-spacing. Use "Display" sizes for hero sections and key insights. Headlines should always be black or white, never crimson, to maintain professional restraint.
- **Body:** Inter is used for all long-form reading to ensure maximum legibility. Line heights are generous (1.6x) to create a relaxed, premium reading pace.
- **Labels:** Small-caps labels with high letter-spacing are a signature element of the design system, used for navigation, categories, and editorial numbering (e.g., 01 / STRATEGY).

## Layout & Spacing

The layout philosophy follows a **Fixed-Column Grid** system that prioritizes generous white space and mathematical order.

- **Desktop:** A 12-column grid with 32px gutters. Content is centered within a 1280px container.
- **Section Padding:** Vertically, sections are separated by a minimum of 120px (section-padding). This "breathable" space is essential to the luxury positioning.
- **Asymmetry:** Use intentional empty columns to create an editorial feel, pushing text to the center or right-aligning it against large photography.
- **Dividers:** Use 1px hairline dividers (Black or Crimson) to separate logical content blocks, spanning the full width of the container.

## Elevation & Depth

This design system rejects traditional shadows and "floating" elements in favor of **Tonal Layering** and flat, structured depth.

- **Flat Stack:** Elements sit directly on the background. Depth is communicated through color blocks (e.g., a white card on a #FAFAFA background) rather than shadows.
- **Refined Micro-Shadows:** Only when necessary for functional clarity (like a sticky header), use a single, highly diffused shadow: `0px 4px 20px rgba(0, 0, 0, 0.03)`. It should be almost imperceptible.
- **Hairlines:** 1px borders are the primary tool for defining boundaries. A Crimson 1px border is used exclusively to denote "Active" or "Highlighted" status.

## Shapes

The shape language is strictly **Sharp (0px)**. 

Every element—from buttons and input fields to service cards and images—must have perfectly square corners. This zero-radius approach reinforces the "unyielding" and "precise" nature of management consulting. Circles are permitted only for small functional icons or bullet points, but never for structural containers.

## Components

### Buttons
- **Primary:** Solid Black background, White text, 0px radius. Hover state: Crimson background.
- **Secondary:** Transparent background, 1px Black border. Hover state: 1px Crimson border with Crimson text.
- **Label:** All-caps, 12px Inter, 0.15em tracking.

### Service Cards
- Flat, white containers with a 1px #E5E5E5 border.
- Top-left corner features an editorial number (e.g., 01) in Crimson Playfair Display.
- Content is bottom-aligned to create an "empty" professional feel in the card center.

### Input Fields
- Underline-style only (1px Black bottom border). 
- Labels sit above the line in small-caps Inter.
- Focus state: Bottom border changes to Crimson.

### Horizontal Timeline
- A 1px Gray line spanning the grid. 
- Crimson dots (8px) represent milestones.
- Active phases are highlighted with a Crimson hairline above the text labels.

### Navigation
- Sticky header with a white background. 
- Text-only links with Crimson underlines that animate in from the center on hover.