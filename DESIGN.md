---
name: Design For Cause
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#ad3300'
  on-secondary: '#ffffff'
  secondary-container: '#fc6b3a'
  on-secondary-container: '#5e1800'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002112'
  on-tertiary-container: '#009764'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fc'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465b'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59e'
  on-secondary-fixed: '#3a0b00'
  on-secondary-fixed-variant: '#842500'
  tertiary-fixed: '#7bfabb'
  tertiary-fixed-dim: '#5ddda1'
  on-tertiary-fixed: '#002112'
  on-tertiary-fixed-variant: '#005234'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  impact-orange: '#ad3300'
  vital-green: '#00a36c'
  foundation-ink: '#131b2e'
  surface-muted: '#eceef0'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base-unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  max-width: 1280px
  section-gap-sm: 80px
  section-gap-md: 120px
  section-gap-lg: 160px
---

## Brand & Style

The design system embodies "Architectural Optimism," balancing the structural rigor of urban planning with the vibrant energy of social progress. It is designed for non-profit leaders, social entrepreneurs, and community organizers who require professional-grade tools that feel purposeful rather than cold or corporate.

The aesthetic is a hybrid of **Modern Minimalism** and **High-Contrast Bold**. It utilizes heavy whitespace and a strict underlying grid to maintain architectural precision, while injecting "human energy" through purposeful splashes of saturated color and large, approachable typography. The interface feels stable yet kinetic—a foundation for active change.

## Colors

The palette is built on a high-contrast functional system designed for clarity and impact.

*   **Primary (Foundation Ink):** A deep navy used for core navigation, borders, and structural text to maintain authority.
*   **Secondary (Impact Orange):** A warm, high-visibility hue reserved for primary actions. It represents the urgency and energy of the mission.
*   **Tertiary (Vital Green):** A professional, vibrant emerald added to suggest growth and impact. This color is used for secondary buttons, success states, and decorative accents that signify progress.
*   **Neutral:** A crisp, cool-toned grayscale system that provides the "gallery space" for content to breathe.

Color application must be surgical: use Impact Orange only for the most critical calls to action, while Vital Green supports secondary paths and validates successful user outcomes.

## Typography

This design system utilizes **Hanken Grotesk** for its primary identity. It offers the precision of a geometric grotesque but with a contemporary, human warmth. For technical data, metadata, and button labels, **JetBrains Mono** provides a structured, monospaced contrast.

Headlines use tight tracking and heavy weights to create a "built" look on the page. Body text maintains generous line heights for maximum accessibility and reading comfort. Small labels and technical data should always appear in the monospaced font to reinforce the architectural metaphor.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy built on an 8px base unit.

*   **Desktop:** A 12-column grid with 24px gutters. Content is centered within a 1280px container with 48px margins to emphasize an editorial feel.
*   **Mobile:** A 4-column grid with 16px margins.
*   **Vertical Rhythm:** Sections are separated by large, deliberate gaps (80px to 160px) to create the "whitespace of a blueprint."

Components use "Padding Brackets"—generous internal horizontal padding paired with tighter vertical padding—to create a wide, stable visual footprint that feels grounded on the page.

## Elevation & Depth

This system rejects soft, ambient shadows in favor of **Tonal Layers** and **Structural Outlines**. Depth is communicated through stacking and crisp borders rather than light simulation.

*   **Surface Hierarchy:** Backgrounds use the lightest neutral. Content containers use white with a 1px solid Foundation Ink border.
*   **The "Impact Lift":** When an element is hovered, it shifts 2px up and to the left, revealing a solid 2px offset shadow behind it (hard-edged, 100% opacity). Use the secondary color for this shadow.
*   **Glassmorphism:** Reserved exclusively for navigation overlays, using a 20px backdrop blur and a thin white border to maintain clarity without losing the structural grid.

## Shapes

The shape language is **Soft (0.25rem)**. While the overall feel is architectural, sharp 0px corners are avoided to ensure the UI feels approachable.

*   **Standard Elements:** Buttons, inputs, and small cards use a 4px (0.25rem) radius.
*   **Large Containers:** Section containers and feature cards use 8px (0.5rem).
*   **Interactive Targets:** Radio buttons and checkboxes maintain the 4px radius, avoiding full circles to keep the rectilinear theme consistent.

## Components

*   **Buttons:** Primary buttons are "Impact Orange" with white text. Secondary buttons use a 2px "Vital Green" border with a matching green text label. All button labels use all-caps JetBrains Mono.
*   **Inputs:** Fields are rectangular with a 1px Foundation Ink border. On focus, the border thickens to 2px and changes to Impact Orange.
*   **Cards:** Architectural cards use a 1px border. They feature a "Header Strip"—a 4px vertical line on the left edge (using Vital Green for impact/growth or Impact Orange for urgent actions) to categorize content.
*   **Progress Indicators:** Use a light grey track with a vibrant Vital Green fill to visually represent "Filling the Mission."
*   **Chips/Badges:** Small, rectangular tags with 2px radius. Use Vital Green for "Active" or "Success" states and Foundation Ink for "Archived" or "Draft" states.
*   **Lists:** Divided by solid 1px horizontal lines. Hover states shift the background to a 5% opacity tint of the secondary or tertiary color depending on the context.