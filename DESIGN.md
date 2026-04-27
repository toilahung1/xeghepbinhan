---
name: Technical Precision
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
  on-surface-variant: '#414755'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bc1'
  primary: '#0058bc'
  on-primary: '#ffffff'
  primary-container: '#0070eb'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#9e3d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c64f00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb595'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7c2e00'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h2:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin: 32px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is built on a foundation of **Technical Minimalism** with a **Corporate Modern** execution. It targets high-stakes professional services—fintech, medtech, and scientific platforms—where clarity and precision are paramount. The brand personality is clinical yet accessible, prioritizing information density without sacrificing visual breathability.

The emotional response should be one of "effortless authority." By utilizing a stark white primary canvas and a high-performance geometric typeface, the UI recedes to let the user's data and workflows take center stage. The style leans into the "Swiss Style" of graphic design: a reliance on rigid grids, significant whitespace, and a single accent color to denote action and intent.

## Colors

The color strategy uses a "True White" (#FFFFFF) background to maximize the perceived brightness and "air" of the interface. 

- **Primary Blue (#007AFF):** Reserved exclusively for primary actions, active states, and critical progress indicators. It provides a high-contrast signal against the white background.
- **Secondary Navy (#0F172A):** Used for primary text and iconography to ensure AAA accessibility and a grounded, professional feel.
- **Surface Neutrals:** A range of cool grays (Slate) are used for borders (#E2E8F0) and secondary backgrounds (#F8FAFC) to define structural boundaries without introducing visual noise.
- **Interactive Tints:** Light washes of the primary blue are used for hover states and subtle highlights.

## Typography

This design system exclusively utilizes **Space Grotesk**, a geometric sans-serif that infuses a technical, slightly futuristic edge into the professional aesthetic. 

Headlines utilize tighter tracking and heavier weights to command attention. Body text is set with generous line heights to ensure long-form legibility in data-heavy environments. Small labels and "meta" information should be set in uppercase with increased letter spacing to provide a rhythmic contrast to the standard sentence-case body text.

## Layout & Spacing

The layout philosophy is a **Fixed-Fluid Hybrid**. On desktop, content is contained within a 1280px max-width 12-column grid. The "spacious" feel is achieved through exaggerated vertical rhythm—using 48px or 64px gaps between major sections.

The system follows an 8px base unit. Component padding should prioritize horizontal space (e.g., a button with 12px vertical and 24px horizontal padding) to maintain a wide, stable visual footprint.

## Elevation & Depth

To maintain the "Clean & Modern" requirement, this design system avoids heavy shadows. Depth is communicated via **Tonal Layers** and **Low-Contrast Outlines**.

- **Level 0 (Base):** Pure white (#FFFFFF).
- **Level 1 (Cards/Containers):** Defined by a 1px solid border (#F1F5F9). No shadow.
- **Level 2 (Popovers/Modals):** A very soft, highly diffused ambient shadow (0px 10px 30px rgba(0, 0, 0, 0.04)) is used only when an element physically floats over the interface.
- **Level 3 (Interactive):** When hovered, cards may transition to a subtle primary-tinted border (#DBEAFE) rather than lifting with a shadow.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the "edge" off the technical typography, making the interface feel modern and engineered rather than cold or brutalist. 

Standard components (inputs, buttons) use 4px (0.25rem) corners. Larger containers like cards or modals use 8px (0.5rem). The only exception is the "Pill" shape, used exclusively for Status Badges/Chips to distinguish them from interactive buttons.

## Components

- **Buttons:** Primary buttons are solid Blue (#007AFF) with white text. Secondary buttons use a white background with a 1px Slate-200 border and Navy text. No gradients.
- **Input Fields:** Use a 1px border. On focus, the border changes to Primary Blue with a 3px soft outer glow (the color of the primary blue at 10% opacity).
- **Cards:** Flat design. Background #FFFFFF, 1px border #E2E8F0. Padding should be generous (default 32px).
- **Status Chips:** Use a subtle background fill (e.g., Success = Soft Green fill with Deep Green text). Shape is always fully rounded (pill).
- **Data Tables:** Remove all vertical grid lines. Use 1px horizontal dividers only. Header row should be in `label-caps` typography style.
- **Navigation:** Top-tier navigation uses high-contrast Navy text with a 2px blue underline for the active state.