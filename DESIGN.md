---
name: Cupertino Precision Showcase
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#edeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#414753'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#717785'
  outline-variant: '#c1c6d6'
  surface-tint: '#005cbb'
  primary: '#0059b5'
  on-primary: '#ffffff'
  primary-container: '#0071e3'
  on-primary-container: '#fcfbff'
  inverse-primary: '#abc7ff'
  secondary: '#5e5e63'
  on-secondary: '#ffffff'
  secondary-container: '#e0dfe4'
  on-secondary-container: '#626267'
  tertiary: '#9b3f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c25100'
  on-tertiary-container: '#fffaf9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#abc7ff'
  on-primary-fixed: '#001b3f'
  on-primary-fixed-variant: '#00458f'
  secondary-fixed: '#e3e2e7'
  secondary-fixed-dim: '#c7c6cb'
  on-secondary-fixed: '#1a1b1f'
  on-secondary-fixed-variant: '#46464b'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb693'
  on-tertiary-fixed: '#341000'
  on-tertiary-fixed-variant: '#7a3000'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.025em
  headline-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Inter
    fontSize: 21px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 19px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.005em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  eyebrow:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.25rem
  margin-md: 2.5rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system channels an uncompromising, modernist consumer technology aesthetic: disciplined, editorial, and serenely confident. It balances hyper-refined industrial craftsmanship with airy, cinematic whitespace. Every element exists to disappear behind the industrial design of the hardware it presents, framing high-resolution product finishes, micro-etched titanium rails, and precision camera modules.

Key stylistic pillars:
- **Cupertino Minimalism:** Content-first hierarchy where generous negative space acts as a structural element, not mere emptiness.
- **Micro-tactile Realism:** Tactile surface treatments subtle enough to feel like precision-machined glass and aerospace-grade aluminum.
- **Editorial Typography:** Dramatic scale contrasts between cinematic display headlines and compact, tracking-adjusted technical spec tables.
- **Refined Interactivity:** Fluid, physics-driven micro-interactions, unobtrusive glass navigation, and confident, deliberate visual hierarchy.

## Colors

The palette is engineered around neutral restraint punctuated by a focused, authoritative electric blue.

- **Background Canvas (`#FBFBFD`):** The signature off-white base that softens glare and provides warmth compared to raw digital white.
- **Elevated Surfaces (`#FFFFFF`):** Reserved for floating cards, interactive segments, modals, and spotlight modules.
- **Deep Contrast Charcoal (`#1D1D1F`):** Used for primary typography, dominant badges, and structural icons to deliver crisp optical density without the harshness of pure `#000000`.
- **Secondary Muted Slate (`#86868B`):** Governs subheadings, secondary labels, disabled states, and technical annotations.
- **Accent Electric Blue (`#0071E3`):** The focused interactive color for links, primary CTAs, active radio toggles, and key feature indicators. Its active hover state is `#0077ED`.
- **Surface Accents & Borders (`rgba(0, 0, 0, 0.06)`):** Hairline precision borders framing white cards over the canvas base.
- **Titanium & Tonal Tints (`#F5F5F7` / `#E8E8ED`):** Alternating specs comparison rows, pill container fills, and inactive switch tracks.

## Typography

The typographic system utilizes **Inter** as an authoritative, high-precision neo-grotesque foundation.

- **Display & Headline Hierarchy:** Headings use tight negative tracking (`-0.02em` down to `-0.04em`) to mirror premium editorial hardware launches. Headlines stay compact vertically without feeling cramped.
- **Eyebrows & Overlines:** Set in uppercase or small semi-bold caps (`label-sm`, `eyebrow`) with subtle open tracking (`+0.02em` to `+0.04em`) to establish crisp section categories (e.g., "CAMERA INNOVATION", "CHIP ARCHITECTURE").
- **Specs & Data Typography:** Spec numbers and comparison values prioritize medium weight (`500` or `600`) with tabular numeric alignment to ensure comparison columns line up seamlessly across multi-tier matrices.

## Layout & Spacing

The layout is built around a structured 12-column responsive fluid grid pinned to a maximum content width of `1280px` for showcases and `1440px` for wide side-by-side spec comparisons.

- **Breakpoints:**
  - `Mobile` (< 768px): 4 columns, `margin: 1.25rem`, `gutter: 1rem`. Sticky sub-navigation docks to screen edges with single-column linear stacks.
  - `Tablet` (768px – 1024px): 8 columns, `margin-md: 2.5rem`, `gutter: 1.5rem`. Comparison grids switch to 2-column scrollable or 2-up views.
  - `Desktop` (> 1024px): 12 columns, `margin-lg: 4rem`, `gutter-lg: 2rem`. Full 3-device or 4-device side-by-side matrices.
- **Vertical Cadence:** Feature sections breathe with expansive spacing (`space-2xl` to `space-3xl`), anchoring the eye to singular hardware elevations before introducing dense technical sheets.

## Elevation & Depth

Depth is tactile yet subtle, avoiding heavy drop shadows in favor of luminous frosted glass and low-contrast contact shadows.

- **Atmospheric Surfaces:** Cards rest on an ambient diffusion shadow: `0 8px 30px rgba(0, 0, 0, 0.04)` combined with an ultra-thin boundary stroke: `1px solid rgba(0, 0, 0, 0.06)`. This lifts elevated white cards cleanly off the `#FBFBFD` background.
- **Frosted Translucent Layers:**
  - Sticky header, sub-bars, and floating comparison trays apply `background: rgba(255, 255, 255, 0.82)` with `backdrop-filter: blur(20px) saturate(180%)` and a bottom hairline divider `rgba(0, 0, 0, 0.08)`.
- **Interactive Hover Elevation:** Hovered comparison cards do not jump drastically in height; they transition subtly to `0 18px 45px rgba(0, 0, 0, 0.08)` and scale fractionally (`scale(1.008)`), preserving calm elegance.

## Shapes

The design uses sculpted, high-radius continuous curves that mirror the corner geometry of modern industrial hardware.

- **Cards & Showcase Modules:** Feature prominent `rounded-xl` (1.5rem / 24px) corners, establishing soft containment for large hero images.
- **Segmented Controls & Filter Bars:** Utilize rounded capsule styling (`rounded-lg` to full-pill `9999px`) where internal active thumbs float with unified corner harmony.
- **Buttons & Chips:** Micro-action pills and finish swatches are strictly rounded-full, echoing tactile buttons on handheld devices.

## Components

### Buttons & Interactive CTAs
- **Primary Action:** Solid `#0071E3` fill, white typography, rounded-full pill shape, padding `12px 24px`. Hover triggers a smooth shift to `#0077ED`.
- **Secondary Action:** Translucent slate pill `rgba(0, 113, 227, 0.08)` with `#0071E3` text. Hover shifts to `rgba(0, 113, 227, 0.14)`.
- **Editorial Link:** `#0071E3` with an inline chevron `›` that animates +3px on hover.

### Segmented Controls & Spec Switchers
- **Container:** Rounded pill container with `#EEEEF0` background and `4px` internal padding.
- **Active Thumb:** Pure `#FFFFFF` surface with `box-shadow: 0 2px 8px rgba(0, 0, 0, 0.12)`, text `#1D1D1F`, transition duration `200ms ease-out`. Inactive segments display `#86868B`.

### Device Comparison Matrix
- **Header Dock:** Sticky top strip showing miniature device renders, titles, starting prices, and Buy links.
- **Spec Rows:** Alternating hairline row dividers (`rgba(0, 0, 0, 0.06)`). Spec labels appear above values in `#86868B`, with primary metrics (e.g., "48MP Main", "Up to 29 hrs video") rendered in semi-bold `#1D1D1F`.
- **Difference Highlighter:** A discrete toggle switch ("Only show differences") that dims matching rows to `0.3` opacity.

### Finish / Color Swatches
- 20px circular discs ringed with a hairline inner shadow.
- Selected state: An external 2px offset border in `#0071E3` with a 2px gap, smoothly rotating the device hero image to the corresponding colorway.

### Accordion & Feature Reveal Modules
- Borderless or thin bottom divider. Trigger headers use `headline-sm` with a slender circular toggle icon `+` that rotates 45 degrees into an `×` when expanded.