---
name: Tradition & Takeaway
colors:
  surface: '#fff8f7'
  surface-dim: '#ebd5d3'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ef'
  surface-container: '#ffe9e7'
  surface-container-high: '#fae3e1'
  surface-container-highest: '#f4dddb'
  on-surface: '#251917'
  on-surface-variant: '#58413f'
  inverse-surface: '#3b2d2c'
  inverse-on-surface: '#ffedeb'
  outline: '#8b716e'
  outline-variant: '#dfbfbc'
  surface-tint: '#aa3531'
  primary: '#6a020a'
  on-primary: '#ffffff'
  primary-container: '#8b1e1e'
  on-primary-container: '#ff9d95'
  inverse-primary: '#ffb3ad'
  secondary: '#b90c17'
  on-secondary: '#ffffff'
  secondary-container: '#de2e2c'
  on-secondary-container: '#fffbff'
  tertiary: '#402f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c4500'
  on-tertiary-container: '#dcb24a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#891c1d'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#93000d'
  tertiary-fixed: '#ffdf99'
  tertiary-fixed-dim: '#ecc158'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#fff8f7'
  on-background: '#251917'
  surface-variant: '#f4dddb'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
  headline-md:
    fontFamily: Montserrat
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
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
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers a warm, artisanal, and highly appetizing experience tailored for traditional Spanish takeaway cuisine. The visual narrative combines the reliability of modern digital ordering with the cozy, trustworthy feel of a neighborhood local favorite. 

### Brand Personality
- **Approachable & Familiar:** Rooted in traditional culinary culture, evoking the warmth of home-cooked meals.
- **Efficient & Conversion-Focused:** Streamlined for rapid decision-making, emphasizing instant actions like WhatsApp ordering and direct phone calls.
- **Clean & Authentic:** Uncluttered layouts that let the food photography and rich, traditional color palette take center stage.

### Design Style
We employ a **Tactile & Warm Modernism** style—characterized by comfortable spacing, organic warmth through color contrast, solid foundational cards, and low-friction interactive elements designed for high intent and quick conversion.

## Colors

The color palette draws directly from classic Spanish culinary tones, creating an immediately appetizing and culturally resonant atmosphere.

- **Primary (`#8B1E1E` - Granate):** Used for primary branding, headers, and key interactive elements to anchor the visual weight.
- **Secondary (`#D62828` - Rojo Cresta):** Applied to high-priority conversion elements, promotional badges, and urgent calls to action.
- **Tertiary (`#C9A13B` - Dorado Mostaza):** Serves as an accent color for ratings, highlights, and secondary tags.
- **Neutral Light (`#FFF9F0` - Crema):** The foundational background color, offering a softer, warmer alternative to stark white.
- **Neutral Dark (`#2A1A14` - Marrón Oscuro):** Used for all body copy and primary structural text to maintain high contrast and readability without harshness.

## Typography

Typography establishes a bold, appetizing hierarchy built for readability across mobile devices. 

- **Headlines:** Set in **Montserrat** (ExtraBold, uppercase where appropriate), giving titles a punchy, geometric, and modern neighborhood feel.
- **Body & Labels:** Set in **Inter**, ensuring pristine legibility for menu descriptions, prices, and small metadata.
- **Responsive Scaling:** Headlines larger than 32px automatically scale down on mobile viewports to prevent awkward wrapping and maintain structural rhythm.

## Layout & Spacing

The layout philosophy centers on a **fluid grid** optimized for mobile-first ordering behavior, where users typically browse menus on smartphones with one thumb.

- **Grid System:** A flexible 12-column layout on desktop that collapses seamlessly into a single-column stack on mobile devices.
- **Spacing Rhythm:** Based on an 8px foundational scale (`space-sm` = 8px, `space-md` = 16px), ensuring comfortable touch targets (minimum 48px height) for quick actions.
- **Margins & Gutters:** Generous outer margins (`1rem` on mobile, scaling to `2rem` on desktop) prevent content from touching screen edges, preserving the warm, uncrowded aesthetic.

## Elevation & Depth

Visual hierarchy relies primarily on **tonal layers** and subtle **ambient shadows** to differentiate interactive cards from the warm cream background.

- **Surface Tiers:** Cards and floating action elements use pure white (`#FFFFFF`) surfaces layered over the cream background (`#FFF9F0`) to create natural depth without harsh borders.
- **Shadow Treatment:** Shadows are soft, low-opacity, and tinted with warm undertones (`rgba(42, 26, 20, 0.08)`) to maintain the inviting, artisanal feel.
- **Interactive Feedback:** Hover and active states elevate cards slightly with increased shadow diffusion, signaling clickable menu items instantly.

## Shapes

With a roundedness setting of **2**, UI elements feature friendly, approachable curves (`0.5rem` base radius, `1rem` for large containers). 

- **Containers & Cards:** Softly rounded corners create an inviting, non-corporate atmosphere that feels handcrafted and local.
- **Buttons & Badges:** Fully rounded or pill-shaped variants are reserved for key conversion triggers (WhatsApp and Call CTAs), guiding the user's eye directly to immediate action points.

## Components

Components are engineered for high visibility, touch-friendliness, and rapid conversion.

- **Buttons:** Primary actions (e.g., "Pedir por WhatsApp", "Llamar Ahora") use high-contrast fills (Granate or Rojo Cresta) with bold labels and generous touch heights (minimum 48px). Secondary buttons use outlined variants with warm neutral borders.
- **Chips & Tags:** Used for dietary flags (Sin Gluten, Casero, Picante) utilizing the mustard gold and soft cream tints for clear categorization.
- **Input Fields:** Clean text inputs featuring rounded borders, high-contrast placeholder text, and clear error states in Rojo Cresta for checkout forms.
- **Cards (Menu Items):** Feature a prominent image area at the top, bold Montserrat titles, short Inter descriptions, clear pricing in bold, and an inline quick-add action.
- **Lists:** Structured with generous vertical padding to ensure easy scanning of menu categories and order summaries.
- **Checkboxes & Radio Buttons:** Custom-styled with primary granate fills to maintain brand consistency during preference selection.