---
name: SecureLogic
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
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fd'
  on-secondary-container: '#57657b'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001a42'
  on-tertiary-container: '#3980f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 20px
  margin: 32px
---

## Brand & Style

The design system for TecnoInnova S.A. is built upon the pillars of **Trust, Precision, and Stability**. As a security systems company, the visual language must communicate unshakeable reliability and technical expertise. 

The chosen style is **Corporate / Modern**, specifically optimized for high-density dashboard environments. It utilizes a "Utility-First" philosophy where clarity takes precedence over decoration. The interface feels architectural—structured by a rigorous grid and clear information hierarchy—to ensure that security personnel can monitor, analyze, and act upon data without cognitive friction. The aesthetic is clean and efficient, favoring subtle tonal shifts over loud visual distractions.

- **Minimalism:** Use generous whitespace between functional groups to prevent data fatigue.
- **Modern Enterprise:** A focus on "Information Density Control," allowing for both high-level overviews and granular data management.
- **Professional Tone:** All interactions are predictable, standard-compliant, and authoritative.

## Colors

The palette is anchored in **Deep Navy (Slate 900)** to represent security and authority. This primary color is used for structural navigation and primary actions. **Slate Grey (Slate 700)** serves as the secondary color for sub-text and secondary iconography, providing a softer but still professional contrast.

**Clean White (#FFFFFF)** and **Ghost White (Slate 50)** form the foundation of the interface, providing a sterile, high-clarity environment for data visualization. **System Blue (Blue 500)** is used sparingly as a tertiary accent to highlight active states, notifications, and primary calls to action, drawing the eye toward critical interactions without overwhelming the slate-heavy aesthetic.

- **Success/Warning/Critical:** Use standard semantic colors (Emerald 600, Amber 500, Rose 600) strictly for status indicators.
- **Backgrounds:** Use Slate 50 for the main application background to reduce eye strain compared to pure white.

## Typography

The typography system prioritizes legibility and technical precision.

- **Hanken Grotesk** is used for headlines. Its sharp, contemporary geometry reinforces the "Innova" aspect of the brand while remaining highly professional.
- **Inter** is the workhorse for all body content and UI elements. Its neutral, systematic design ensures readability in dense data tables and complex forms.
- **JetBrains Mono** is utilized for labels, technical ID numbers, and timestamps. This monospaced font provides a "command-center" feel and ensures that numerical data aligns perfectly in vertical columns.

For mobile, headlines scale down to prevent excessive wrapping, while body sizes remain constant to ensure accessibility in the field.

## Layout & Spacing

This design system employs a **12-column fluid grid** for desktop dashboards, allowing for flexible widgets and data visualizations. 

- **8pt Grid System:** All spacing, margins, and gutters are multiples of 4px/8px to ensure mathematical harmony and ease of implementation.
- **Dashboard Layout:** Standard layout includes a fixed 240px left sidebar for primary navigation and a flexible main content area.
- **Density:** Use 'md' (16px) as the default internal padding for cards and containers. For data-heavy tables, reduce vertical padding to 'sm' (8px) to maximize information display.
- **Breakpoints:**
  - **Desktop (1280px+):** 12 columns, 32px margins.
  - **Tablet (768px - 1279px):** 6 columns, 24px margins.
  - **Mobile (0px - 767px):** 2 columns, 16px margins, sidebar collapses into a hamburger menu.

## Elevation & Depth

To maintain a professional and "flat" modern aesthetic, this design system avoids heavy shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Levels:** 
  - Level 0 (Background): Slate 50.
  - Level 1 (Cards/Panels): Pure White with a 1px border of Slate 200.
  - Level 2 (Modals/Popovers): Pure White with a 1px border and a subtle, extra-diffused shadow (0px 10px 15px -3px rgba(15, 23, 42, 0.08)).
- **Separation:** Use border-based separation rather than shadows for sidebar and header areas to maintain a crisp, blueprint-like feel.
- **Interactive States:** Hovering over a card or list item should trigger a subtle shift in background color (e.g., from White to Slate 50) rather than an elevation lift.

## Shapes

The shape language is conservative and disciplined. A **Soft (0.25rem)** corner radius is the standard for almost all UI elements, including buttons, input fields, and small containers.

- **Standard (rounded):** 4px (0.25rem). Used for buttons, inputs, and tags.
- **Large (rounded-lg):** 8px (0.5rem). Used for main dashboard cards and containers.
- **Pill:** Fully rounded edges are reserved exclusively for status "badges" (e.g., Active, Offline, Pending) to distinguish them from interactive buttons.

## Components

### Buttons
- **Primary:** Solid Navy (#0F172A) with white text. No shadow.
- **Secondary:** White background with Navy border and text.
- **Ghost:** No background or border; navy text. Used for less frequent actions.

### Input Fields
- White background, 1px Slate 200 border.
- Active state: 1px Blue 500 border with a 2px soft blue focus ring (low opacity).
- Labels: Placed above the field in Inter Medium, 12px.

### Cards
- White fill, 1px Slate 200 border.
- Headers within cards should have a subtle bottom border (1px Slate 100) to separate the title from content.

### Chips & Badges
- **Status Badges:** Pill-shaped, light pastel backgrounds with dark text of the same hue (e.g., Light Green background with Dark Green text for "Secure").
- **Interactive Chips:** Rectangular (4px radius) with Slate 100 background.

### Data Tables
- Row height: 48px.
- Zebra striping: Use Slate 50 for even rows.
- Header: Slate 100 background with JetBrains Mono labels for technical columns.

### Specific Security Components
- **CCTV Feed Container:** 4px rounded corners, black background, overlaying JetBrains Mono "Rec" or "Live" labels in the top right.
- **Alert Banner:** Full-width top banner using semantic colors (Red for high-priority intrusion alerts) with a bold border.