---
name: Obsidian Dynamics
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#bac9cc'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#849396'
  outline-variant: '#3b494c'
  surface-tint: '#00daf3'
  primary: '#c3f5ff'
  on-primary: '#00363d'
  primary-container: '#00e5ff'
  on-primary-container: '#00626e'
  inverse-primary: '#006875'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#b3f9ff'
  on-tertiary: '#00363a'
  tertiary-container: '#7fdfe8'
  on-tertiary-container: '#006369'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#9cf0ff'
  primary-fixed-dim: '#00daf3'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#92f2fa'
  tertiary-fixed-dim: '#75d5de'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
  surface-base: '#0B0F17'
  surface-elevated: '#111827'
  surface-overlay: '#1E293B'
  border-glass: rgba(255, 255, 255, 0.08)
  border-active: rgba(0, 229, 255, 0.4)
  glow-cyan: rgba(0, 229, 255, 0.15)
  text-primary: '#F8FAFC'
  text-secondary: '#94A3B8'
  text-muted: '#64748B'
  ice-cyan: '#BAE3F8'
  success: '#10B981'
  warning: '#F59E0B'
  danger: '#EF4444'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.06em
  label-badge:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system expresses high-conviction enterprise expertise, combining surgical technical competence with modern dark-mode aesthetics. Designed specifically for specialized enterprise ERP and Microsoft Dynamics 365 Business Central consulting, the aesthetic projects authority, reliability, and algorithmic precision.

The visual direction merges **Minimalism** with **Dark Glassmorphism**:
- Ultra-deep obsidian canvases that reduce visual fatigue during heavy data interaction and consulting workflows.
- Electric cyan accents acting as functional light sources rather than mere decoration—directing eye movement to critical system signals, ROI conversions, and key CTA touchpoints.
- Architectural card structures, micro-borders, and disciplined typography that project the engineering rigor required by enterprise architectures.

## Colors

The palette operates on a strict functional hierarchy built on dark obsidian foundations:
- **Primary (`#00E5FF`)**: Pure electric cyan reserved for primary conversion triggers, active navigation items, progress indicators, and focal metric callouts.
- **Secondary (`#06B6D4`)**: Saturated cyan supporting secondary actions, interactive hover states, and structural icons.
- **Tertiary (`#00828A`)**: Deep teal derived from the original brand heritage, establishing stability in container headers, data table accent rows, and tag fills.
- **Neutral (`#0B0F17`)**: Base void canvas, paired with `#111827` (elevated card backgrounds) and `#1E293B` (popovers, active rows, dialogs) to form clear spatial elevation.
- **Border Glass (`rgba(255, 255, 255, 0.08)`)**: Provides crisp separation between surfaces without relying on heavy solid lines or opaque dividers.

## Typography

The typographic system utilizes a disciplined dual-sans pairing combined with a technical monospaced role:
- **Headlines (Plus Jakarta Sans)**: Delivers geometric confidence, crisp geometric letterforms, and high legibility at massive display sizes. Tight letter spacing (`-0.02em` to `-0.03em`) on major headlines reinforces a modern enterprise posture.
- **Body & Structural Text (Inter)**: The standard for enterprise UI, rendering complex data grids, functional workflows, and technical consulting deliverables with zero glyph ambiguity.
- **Technical & Metric Accents (JetBrains Mono)**: Applied to metadata pills, ERP entity codes, status tags, version numbers, and API references, validating technical proficiency.

## Layout & Spacing

The layout model implements an 8pt base grid within a 12-column responsive layout container (max width 1320px). 

- **Breakpoints**: Mobile (0–767px), Tablet (768–1023px), Desktop (1024–1439px), and Large Display (1440px+).
- **Desktop (12 Columns)**: 1.5rem gutters, 3rem screen margins. Complex dashboard grids span 3, 4, 6, or 12 units to house side-by-side telemetry and module workflows.
- **Tablet (8 Columns)**: 1.25rem gutters, 2rem screen margins. Analytics modules transition to half-width containers.
- **Mobile (4 Columns)**: 1rem gutters, 1.25rem margins. Cards and tables reflow into single-column vertical cards.

## Elevation & Depth

Visual depth is achieved through **Tonal Layering** and **Subtle Glassmorphism** rather than heavy drop shadows:

- **Surface Grounding**: 
  - Level 0 (Base Canvas): `#0B0F17` (Deep Obsidian).
  - Level 1 (Cards, Modules): `#111827` backed by an ultra-thin border `1px solid rgba(255, 255, 255, 0.08)`.
  - Level 2 (Modals, Overlays, Dropdowns): `#1E293B` backed by `1px solid rgba(255, 255, 255, 0.12)` with `backdrop-filter: blur(12px)`.
- **Glow & Interactive Fields**:
  - Hover states and primary active components introduce an outer halo rather than a standard shadow: `box-shadow: 0 0 24px -4px rgba(0, 229, 255, 0.25)`.
  - Ambient backdrops use soft, oversized radial gradients (`radial-gradient(circle at 50% 0%, rgba(0, 229, 255, 0.05), transparent 70%)`) to create cinematic depth behind key headlines and card groups.

## Shapes

The design system adopts a **Soft (Level 1)** geometric standard. This geometry balances technical precision with modern enterprise UI trends:
- Standard interactive elements (inputs, standard buttons, badge pills) utilize `0.375rem` (6px) or `0.25rem` (4px).
- Structural containers (cards, data tables, modular panels) employ `0.5rem` (8px).
- Modals, flyout dialogs, and hero showcase frames leverage `0.75rem` (12px).
- Rounded pill formats are reserved exclusively for status badges and live system telemetry indicators.

## Components

### Buttons
- **Primary**: Solid Electric Cyan background (`#00E5FF`), bold near-black text (`#0B0F17`), `0.375rem` radius, subtle glow on hover (`box-shadow: 0 0 20px rgba(0, 229, 255, 0.35)`).
- **Secondary**: Elevated dark background (`#111827`), glass border (`1px solid rgba(255, 255, 255, 0.12)`), text `#F8FAFC`. On hover, border transitions to `rgba(0, 229, 255, 0.4)` with text turning `#00E5FF`.
- **Ghost**: Transparent background, text `#94A3B8`. On hover, text `#00E5FF` with background `rgba(0, 229, 255, 0.06)`.

### Cards & Enterprise Modules
- Background `#111827`, border `1px solid rgba(255, 255, 255, 0.08)`, radius `0.5rem`.
- Padding `space-lg` (1.5rem) on desktop, `space-md` (1rem) on mobile.
- Cards maintain crisp vertical hierarchy: Top category pill or icon, followed by `headline-md`, supporting `body-sm` description, and terminal metrics or action link.

### Badges & Status Chips
- Height 24px, uppercase `label-badge` typography, pill radius (`9999px`).
- **Telemetry Active**: `rgba(0, 229, 255, 0.1)` fill, `#00E5FF` text, pulsing 6px dot.
- **Neutral Tag**: `rgba(255, 255, 255, 0.05)` fill, `#94A3B8` text, `1px solid rgba(255, 255, 255, 0.08)`.

### Input Fields & Controls
- Base background `#0B0F17`, border `1px solid rgba(255, 255, 255, 0.12)`, radius `0.375rem`, text `#F8FAFC`.
- Focus state: Border transitions to `#00E5FF`, accompanied by `0 0 0 1px #00E5FF` focus ring.
- Checkboxes & Radios: `#0B0F17` fill with `1px solid rgba(255, 255, 255, 0.2)`. When checked, solid `#00E5FF` fill with dark `#0B0F17` checkmark icon.

### Data Tables & Lists
- Crisp row dividers using `rgba(255, 255, 255, 0.04)`.
- Alternating subtle stripe or hover highlight with `rgba(0, 229, 255, 0.03)`.
- Headers set in `JetBrains Mono` (`label-code`) in `#64748B`, with right-aligned numeric data for financial and ERP ledger clarity.