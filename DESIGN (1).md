---
name: Finash Core
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#3d4946'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#6d7a76'
  outline-variant: '#bccac5'
  surface-tint: '#006b5c'
  primary: '#006b5c'
  on-primary: '#ffffff'
  primary-container: '#2bb19b'
  on-primary-container: '#003d34'
  inverse-primary: '#5fdac3'
  secondary: '#006e0d'
  on-secondary: '#ffffff'
  secondary-container: '#88fc7a'
  on-secondary-container: '#00750f'
  tertiary: '#4b635e'
  on-tertiary: '#ffffff'
  tertiary-container: '#8aa49e'
  on-tertiary-container: '#223a36'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7ef7de'
  primary-fixed-dim: '#5fdac3'
  on-primary-fixed: '#00201b'
  on-primary-fixed-variant: '#005045'
  secondary-fixed: '#88fc7a'
  secondary-fixed-dim: '#6cdf61'
  on-secondary-fixed: '#002201'
  on-secondary-fixed-variant: '#005307'
  tertiary-fixed: '#cde8e2'
  tertiary-fixed-dim: '#b2ccc6'
  on-tertiary-fixed: '#071f1c'
  on-tertiary-fixed-variant: '#334b47'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
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
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  margin-page: 40px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is engineered for a high-end SaaS environment where financial precision meets modern agility. The brand personality is rooted in "Dynamic Stability"—conveying the energy of growth through vibrant greens while maintaining a grounded, professional atmosphere through structured layouts and expansive white space. 

The aesthetic follows a **Corporate / Modern** style, borrowing the "less is more" philosophy of minimalism. It prioritizes clarity and conversion, using high-contrast typography and intentional pops of brand color to guide user focus toward key actions and data insights. The visual language evokes a sense of premium reliability, suitable for a sophisticated business audience.

## Colors

The color strategy revolves around a dual-accent system of teal and lime, balanced against a pristine architectural foundation. 

- **Primary Teal (#2BB19B):** Extracted from the logo's core, this is the functional workhorse. Use it for primary calls-to-action, active states, and critical links.
- **Secondary Lime (#7DF070):** Used sparingly as a "highlight" color for progress bars, success indicators, and subtle decorative gradients to provide a sense of vibrancy and growth.
- **Tertiary Deep Teal (#122A26):** A dark, near-black shade used for footers or sidebars to provide visual weight and depth.
- **Neutrals:** The background is strictly white (#FFFFFF) to maximize contrast, with #F8F9FA utilized for section offsets and container backgrounds to create a subtle "layered" effect.

## Typography

This design system utilizes a high-contrast typographic pairing to balance modern flair with institutional readability.

- **Headlines:** Plus Jakarta Sans is the primary choice for marketing and display text. Its geometric yet friendly curves feel premium and tech-forward. Bold and Extra Bold weights should be used for large headings to create a clear visual hierarchy.
- **Body & Interface:** Inter provides the necessary utilitarian clarity for data-heavy sections. It is used for all UI components, long-form text, and labels.
- **Contrast:** Ensure all body text is a deep charcoal (#111827) rather than pure black to maintain a sophisticated feel while meeting high accessibility standards.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop to ensure a controlled, premium reading experience, transitioning to a fluid layout for mobile devices.

- **Grid:** A 12-column grid with 24px gutters is the standard for component placement. 
- **Rhythm:** Spacing follows an 8px base unit. Vertical rhythm is established using "Stack" variables to separate sections (48px) from internal card elements (24px).
- **Margins:** Generous outer margins (40px+) are encouraged to provide "breathing room" which is a hallmark of high-end SaaS design. 
- **Density:** Maintain a medium-to-low density. Information should feel accessible, never cramped.

## Elevation & Depth

Visual hierarchy is achieved through a combination of **Ambient Shadows** and **Tonal Layering**. 

- **Shadows:** The signature shadow for this design system is highly diffused: `0 10px 30px rgba(0,0,0,0.05)`. This creates a sense of the UI floating slightly above the background without creating harsh edges.
- **Layering:** Use the secondary background color (#F8F9FA) for "wells" or large background sections. White (#FFFFFF) is reserved for the highest level of the Z-axis (cards and floating menus).
- **Depth Gradients:** Apply very subtle linear gradients (e.g., White to #F9FAFB) within large cards or buttons to provide a polished, tactile feel that prevents the UI from looking overly flat.

## Shapes

The shape language is defined by **Rounded** geometry, which softens the professional aesthetic and makes the interface feel more approachable.

- **Cards:** Use a standard radius of 16px to create a soft, friendly container for content.
- **Buttons & Inputs:** Use a radius of 12px. This slightly tighter corner ensures that interactive elements look precise and "clickable" compared to the larger container cards.
- **Icons:** Should be contained within circular or 12px rounded-square enclosures when used in a feature list.

## Components

Consistency across components reinforces the brand's premium positioning.

- **Buttons:**
  - **Primary:** Solid Teal (#2BB19B) with white text. Apply a subtle top-down gradient (lightening by 5% at the top) for a polished finish.
  - **Secondary:** Outlined with a 1px border of #E5E7EB and #111827 text.
- **Cards:** Always white background, 16px radius, and the signature 0 10px 30px soft shadow. Use a 1px stroke of #F3F4F6 for extra definition on white backgrounds.
- **Inputs:** 12px radius, #F8F9FA background, and a 1px #E5E7EB border. On focus, the border should transition to Primary Teal with a subtle outer glow.
- **Chips:** Small, 100px (pill) radius, using a desaturated tint of the primary color (e.g., 10% opacity teal background with 100% teal text).
- **Data Visuals:** Charts and graphs should utilize the full brand palette (Teal, Lime, and Charcoal) to maintain a cohesive look with the logo.