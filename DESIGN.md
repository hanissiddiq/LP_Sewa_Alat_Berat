---
name: Nusantara Industrial Framework
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
  on-surface-variant: '#43474f'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737780'
  outline-variant: '#c3c6d0'
  surface-tint: '#396092'
  primary: '#00274e'
  on-primary: '#ffffff'
  primary-container: '#0f3d6e'
  on-primary-container: '#84a9e0'
  inverse-primary: '#a5c8ff'
  secondary: '#8d4f00'
  on-secondary: '#ffffff'
  secondary-container: '#fe9824'
  on-secondary-container: '#663800'
  tertiary: '#1c2738'
  on-tertiary: '#ffffff'
  tertiary-container: '#323d4f'
  on-tertiary-container: '#9ca8bd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#a5c8ff'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#1e4879'
  secondary-fixed: '#ffdcc0'
  secondary-fixed-dim: '#ffb875'
  on-secondary-fixed: '#2d1600'
  on-secondary-fixed-variant: '#6b3b00'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  headline-sm:
    fontFamily: Montserrat
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
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for the heavy industry sector, prioritizing reliability, safety, and institutional strength. The visual narrative balances the rugged nature of construction and mining with a sophisticated B2B corporate layer. 

The style is **Corporate / Modern**, characterized by structured layouts, high-integrity alignment, and a premium finish. It avoids unnecessary decorative elements, focusing instead on clarity and functional confidence. The UI should feel "heavy" in its stability but "light" in its digital execution, utilizing generous whitespace to ensure that complex technical data remains digestible for procurement officers and site managers alike.

## Colors

The palette is anchored by **Deep Blue (#0F3D6E)**, representing authority, trust, and the "Nusantara" corporate identity. This is the primary color for navigation, headers, and primary structural elements.

**Construction Orange (#F7931E)** serves as the high-visibility accent. It is reserved strictly for primary actions, status indicators related to safety or urgency, and key interactive highlights. 

The neutral scale utilizes a cool-toned **Light Gray (#F8FAFC)** for backgrounds to maintain a clean, modern atmosphere, while **White (#FFFFFF)** is used for content containers to provide maximum contrast and legibility. Functional colors (Success, Warning, Error) follow standard industry conventions but are slightly desaturated to maintain the premium corporate aesthetic.

## Typography

This design system employs a dual-font strategy. **Montserrat** is used for headlines to convey strength and industrial precision through its geometric, bold character. **Inter** is utilized for all body text and UI labels to ensure exceptional readability in data-heavy contexts, such as equipment specifications or rental agreements.

Headlines should use tight letter-spacing to appear more impactful. Body text maintains a generous line-height to reduce cognitive load. All labels and metadata should use Inter to ensure clarity at smaller scales.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile devices. 

The spacing rhythm is based on an **8px base unit**. 
- **Desktop:** 64px outer margins with 24px gutters. Content is capped at a 1280px max-width to maintain readability.
- **Tablet:** 32px outer margins with 20px gutters.
- **Mobile:** 20px outer margins with 16px gutters.

The "stack" methodology (sm, md, lg) should be used to define vertical rhythm between components. A "generous whitespace" rule is applied: when in doubt, increase vertical padding to maintain a premium, uncluttered feel.

## Elevation & Depth

This design system uses **Tonal Layers** supplemented by **Ambient Shadows** to define hierarchy. 

1. **Surface (Background):** #F8FAFC - The base canvas.
2. **Layer 1 (Cards/Containers):** #FFFFFF - Primary content area with a subtle 1px border (#E2E8F0) and a soft, low-opacity shadow (Y: 4px, Blur: 12px, Color: rgba(15, 61, 110, 0.05)).
3. **Layer 2 (Hover/Active):** Increased shadow depth (Y: 8px, Blur: 20px, Color: rgba(15, 61, 110, 0.1)) and a slight upward translation (2px) to indicate interactivity.

Shadows should always carry a minute amount of the Primary Deep Blue tint to maintain color harmony across the system.

## Shapes

The design system utilizes **Rounded (Level 2)** settings to soften the industrial nature of the brand while remaining professional. 

- **Standard Components (Buttons, Inputs, Small Cards):** 0.5rem (8px) radius.
- **Large Components (Modals, Large Feature Cards):** 1rem (16px) radius.
- **Specialty Elements (Search Bars, Tags):** Full pill-shape where appropriate to distinguish from structural containers.

This medium roundedness creates a "modern-industrial" feel—sturdy yet accessible.

## Components

### Buttons
- **Primary:** Deep Blue background, White text. High-emphasis.
- **Action/CTA:** Construction Orange background, White text. Reserved for "Book Now" or "Inquire."
- **Secondary:** Ghost style with Deep Blue border and text.
- **State:** 0.5rem radius; subtle 200ms transition on hover with a brightness adjustment.

### Cards
Cards are the primary vessel for equipment listings. They feature a White background, the Layer 1 shadow, and a 1px border. On hover, the border color shifts to Primary Blue and the shadow deepens.

### Input Fields
Inputs must feel stable. Use a White background with a 1px #CBD5E1 border. On focus, the border shifts to Deep Blue with a 2px soft outer glow. Labels are Inter Semi-bold (14px) positioned above the field.

### Lists & Specs
For heavy equipment specifications, use a "Zebrastripe" list format or a clean grid with light gray dividers (#F1F5F9). Icons used within specs should be mono-lineal and colored in Primary Blue.

### Chips/Status Indicators
- **Available:** Light green background with dark green text.
- **On Rent:** Light blue background with Deep Blue text.
- **Maintenance:** Light orange background with Construction Orange text.
All chips use a pill-shape (Rounded Level 3).