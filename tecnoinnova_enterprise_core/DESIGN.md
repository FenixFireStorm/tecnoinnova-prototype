---
name: Tecnoinnova Enterprise Core
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
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#0b1c30'
  on-tertiary-container: '#75859d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-sm:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  data-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
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
  xl: 32px
  gutter: 16px
  margin-desktop: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system for Tecnoinnova S.A. is built upon the pillars of **Precision, Security, and Efficiency**. As a security systems provider, the UI must reflect the reliability of the physical hardware the company installs. 

The aesthetic is **Corporate Modern**, prioritizing information density and functional clarity over decorative flair. The interface is designed for power users who manage complex workflows—logistics, inventory, and billing—requiring a calm, focused environment that reduces cognitive load during long work sessions. 

Key attributes:
- **Functional Minimalism:** Every element serves a purpose; whitespace is used strategically to separate logical data groups.
- **Systematic Order:** Heavy reliance on structured grids and clear hierarchies.
- **Trust-Based Palette:** Deep blues and steady grays evoke a sense of institutional stability.

## Colors

The palette is anchored in **Navy Blue (#0F172A)** to signify authority and professional rigor. **Royal Blue (#2563EB)** is used as the primary action color, providing high visibility for interactive elements against the neutral background.

- **Primary:** Deep navy for headers, primary navigation, and high-level text.
- **Secondary:** Vibrant blue for call-to-actions, links, and active states.
- **Neutral:** A refined scale of grays (from Slate to Ghost White) to define surface areas, borders, and secondary text.
- **Semantic:** Standardized success, warning, and error colors for status indicators in inventory and billing modules (e.g., "Stock Low" or "Invoice Overdue").

## Typography

This design system utilizes **Hanken Grotesk** as the primary typeface for its exceptional legibility and modern, sharp terminals. It provides a contemporary "tech-forward" feel while remaining highly readable in data-heavy tables.

**JetBrains Mono** is introduced for specific technical data points, such as SKU numbers, invoice IDs, and tracking codes, helping users distinguish between prose and raw system identifiers at a glance.

- **Scale:** Small increments between sizes (11px to 14px) are utilized to maximize the amount of information visible on a single screen without sacrificing clarity.
- **Hierarchy:** Use bold weights for headers and medium weights for table column labels.

## Layout & Spacing

The system uses a **Fixed-Fluid Hybrid** grid. The primary navigation is fixed to the left, while the content area is a fluid 12-column grid that expands to fill the viewport.

- **Data Density:** A tight 4px baseline grid ensures that ERP tables and forms remain compact. 
- **Gutters:** Standard 16px gutters are used between columns to prevent information bleed.
- **Margins:** Large views (Inventory/Billing lists) use 24px outer margins on desktop to provide breathing room.
- **Breakpoints:**
  - **Desktop (1280px+):** Full 12-column layout with persistent sidebar.
  - **Tablet (768px - 1279px):** 8-column layout; sidebar collapses to icons.
  - **Mobile (<767px):** 4-column layout; vertically stacked forms; top navigation bar.

## Elevation & Depth

To maintain a "professional and clean" appearance, this design system avoids heavy shadows, instead using **Tonal Layering** and **Low-Contrast Outlines**.

- **Level 0 (Background):** Used for the main application background (#F8FAFC).
- **Level 1 (Surfaces):** White (#FFFFFF) cards or containers for content, defined by a 1px border (#E2E8F0).
- **Level 2 (Interaction):** Subtle, tight shadows (4px blur, 10% opacity) are reserved exclusively for floating elements like dropdown menus, tooltips, and modals to separate them from the work surface.
- **Active State:** Elements being edited or focused use a 2px blue ring rather than a shadow change.

## Shapes

The design system employs a **Soft (0.25rem)** roundedness. This "near-sharp" approach maintains the professional, architectural feel of a security firm while preventing the UI from feeling dated or overly aggressive.

- **Standard Elements:** 4px (0.25rem) radius for buttons, input fields, and tags.
- **Large Containers:** 8px (0.5rem) radius for main content cards and dashboard widgets.
- **Status Indicators:** Small status dots or chips use a full pill shape to distinguish them from interactive buttons.

## Components

### Buttons
- **Primary:** Solid Royal Blue with white text. High emphasis for "Create Invoice" or "Confirm Shipment."
- **Secondary:** Ghost style (Transparent with Navy border). For "Cancel" or "Export."
- **Icon-Only:** Used for table actions (Edit/Delete) to save horizontal space.

### Input Fields
- **Design:** Outlined with 1px Slate-200 border. Labels are always persistent above the field.
- **Validation:** Error states use a red border and a 12px helper text below the field.

### Data Tables (Critical Component)
- **Header:** Light gray background (#F1F5F9) with bold 11px uppercase labels.
- **Rows:** Alternating "zebra" stripes are avoided; instead, use subtle 1px bottom borders. Hover states highlight the entire row in a light blue tint.
- **Density:** Cell padding is restricted to 8px vertical to maximize row count.

### Chips & Status Tags
- **Logistics Status:** Small, low-saturation backgrounds with high-saturation text (e.g., "In Transit" = Light Blue bg, Dark Blue text).

### Inventory Cards
- Dashboard-level summaries of stock. Use large Hanken Grotesk numbers for "Items Low on Stock" or "Pending Installations."