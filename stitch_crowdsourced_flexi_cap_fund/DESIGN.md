---
name: Kinetic Capital
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
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
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
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The design system focuses on institutional trust filtered through a modern, tech-forward lens. The target audience includes sophisticated retail investors and community-driven fund managers who value transparency and precision. 

The visual style is **Minimalist with Corporate Modern influences**. It utilizes expansive whitespace to reduce cognitive load during complex financial decision-making. The aesthetic relies on structural integrity—clean lines, purposeful alignment, and a "less is more" philosophy—to evoke an emotional response of stability, clarity, and professional rigor.

## Colors

The palette is anchored by **Deep Navy** (#0F172A), used for primary branding, high-level navigation, and headings to establish authority. **Vibrant Mint** (#10B981) serves as the functional accent color, reserved for growth indicators, primary "Call to Action" buttons, and successful states. 

**Slate Gray** (#64748B) provides a sophisticated mid-tone for secondary text and iconography, ensuring the UI feels layered rather than flat. Backgrounds should primarily utilize the **Neutral** off-white (#F8FAFC) to maintain a soft, paper-like quality that reduces eye strain compared to pure white.

## Typography

The design system exclusively utilizes **Inter** for its exceptional legibility in data-heavy environments. The typographic hierarchy relies on weight and subtle tracking adjustments rather than drastic size changes. 

- **Display & Headlines:** Use tighter letter spacing and Semi-Bold/Bold weights to create a strong visual anchor.
- **Body Text:** Uses a standard weight with generous line-height to ensure financial disclosures and fund descriptions are easily digestible.
- **Labels:** Small labels utilize a slightly heavier weight (Medium/Semi-Bold) and uppercase styling for "Table Headers" or "Overlines" to provide clear structural categorization.

## Layout & Spacing

This design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy emphasizes "Information Tiers"—grouping related financial data into distinct containers with significant breathing room between sections.

- **Desktop:** 12 columns, 24px gutters, and a maximum container width of 1280px to prevent line lengths from becoming unreadable.
- **Mobile:** 4 columns with 16px side margins.
- **Rhythm:** Use an 8px base unit for all spacing (8, 16, 24, 32, 48, 64). Larger gaps (64px+) should be used to separate major logical blocks like "Portfolio Overview" from "Project Roadmap."

## Elevation & Depth

To maintain a sense of "Trust and Clarity," elevation is achieved through a combination of **low-contrast outlines** and **ambient shadows**.

- **Surfaces:** Use a white background for primary content cards against the off-white neutral global background.
- **Shadows:** Apply a singular, very soft shadow style for floating elements (e.g., dropdowns or active cards). Use a 15% opacity Deep Navy tint with a high blur radius (20px-30px) and a subtle vertical offset.
- **Borders:** Define containers with a 1px border in a very light slate (#E2E8F0). This provides structure without the visual "noise" of heavy shadows, reinforcing the minimalist aesthetic.

## Shapes

The shape language is **Soft**, striking a balance between the clinical sharpness of traditional finance and the approachability of modern fintech. 

- **Standard Elements:** Buttons, input fields, and small cards use a 4px (0.25rem) radius.
- **Large Containers:** Dashboard widgets and main content areas use an 8px (0.5rem) radius.
- **Interactive States:** Maintain consistent corner radii across all states to ensure the UI feels grounded and predictable.

## Components

### Buttons
- **Primary:** Deep Navy background with white text. No shadow on rest, subtle lift on hover.
- **Secondary (Mint):** Reserved for "Buy," "Confirm," or "Join Fund" actions.
- **Ghost:** Slate Gray border and text, used for secondary actions like "View Details."

### Form Fields & Stock Selection
- **Inputs:** 1px Slate-200 border, 4px radius. Focus state uses a 2px Mint green ring with 20% opacity.
- **Stock Ticker Chips:** Small, rounded-sm containers with a light gray background and bolded navy text for the symbol.

### Progress & Indicators
- **Fund Roadmap:** A vertical or horizontal linear stepper using Mint for completed phases and Slate for upcoming ones.
- **Funding Bar:** A thick 8px track with a Mint green fill to visualize the progress toward the fund's crowdsourcing goal.

### Cards
- **Info Sections:** White fill, 1px border (#E2E8F0), 8px corner radius. Headlines inside cards should always be Deep Navy.
- **Data Tables:** Minimalist styling with no vertical borders. Use 1px horizontal dividers and highlight rows on hover with the neutral background color.