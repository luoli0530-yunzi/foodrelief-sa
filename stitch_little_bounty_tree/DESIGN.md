---
name: Vibrant Growth
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf4'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dde9ff'
  surface-container-highest: '#d5e3fd'
  on-surface: '#0d1c2f'
  on-surface-variant: '#3c4a42'
  inverse-surface: '#233144'
  inverse-on-surface: '#ebf1ff'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed01b'
  on-secondary-container: '#6f5900'
  tertiary: '#944a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ef8933'
  on-tertiary-container: '#5c2c00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffe083'
  secondary-fixed-dim: '#eec200'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#713700'
  background: '#f8f9ff'
  on-background: '#0d1c2f'
  surface-variant: '#d5e3fd'
typography:
  headline-xl:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The brand personality is energetic, nurturing, and whimsically community-focused. This design system is built to evoke feelings of optimism, growth, and approachability. 

The visual style blends **Modern Minimalism** with **High-Contrast / Bold** elements. It utilizes wide-open spaces and a clean canvas to allow high-saturation accents to pop, creating a "digital garden" aesthetic that feels both professional and playful. The interface avoids cold, clinical whites in favor of warmth and organic vitality.

## Colors
The palette is centered around a "Super-Charged Nature" theme. 

- **Primary Green:** An energetic, highly saturated Emerald (#10B981) that signifies life and action. 
- **Secondary Yellow:** A bright, sunny Goldenrod (#FACC15) used for highlights, alerts, and moments of delight.
- **Warm Background:** To maintain a "clean" but communal feel, the main background uses a very high-lightness cream (#FCFDF7). This prevents the UI from feeling sterile while ensuring maximum contrast for text.
- **Neutrals:** Deep Slate (#334155) provides a grounded anchor for typography, ensuring legibility against the vibrant accents.

## Typography
This design system employs a pairing that balances quirkiness with clarity. 

**Bricolage Grotesque** is used for headlines to provide a distinctive, expressive character. Its unique construction feels organic and modern, perfect for a community-focused product.

**Plus Jakarta Sans** is used for all body text and UI labels. It offers a friendly, rounded geometric structure that maintains high legibility across small screens while complementing the whimsical nature of the display type. Large headlines should use tight line heights and negative letter spacing to feel impactful and "lush."

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous breathing room to reinforce the "growth" narrative. 

- **Desktop:** 12-column grid with 64px outside margins.
- **Mobile:** 4-column grid with 16px margins.
- **Rhythm:** An 8px base unit governs all spatial relationships. Elements should feel "airy"—prefer padding over borders to define structure. Use the "lg" (48px) and "xl" (80px) spacing tokens for vertical sectioning to create a sense of calm and focus.

## Elevation & Depth
To keep the design clean and vibrant, depth is achieved through **Tonal Layers** and **Soft Ambient Shadows**. 

Instead of heavy black shadows, use "Tinted Shadows"—low-opacity dropshadows that inherit a hint of the Primary Green or Neutral Slate color. This keeps the elevation feeling natural rather than synthetic. 

Surfaces should primarily be defined by subtle shifts in color (e.g., a white card on a #FCFDF7 background) rather than harsh outlines. For high-interaction elements like buttons, a slight "pop" shadow is encouraged to make them feel tactile and "pressable."

## Shapes
The shape language is overtly friendly and "bouncy." 

By using **Pill-shaped (Level 3)** roundedness, the design system eliminates sharp corners, which can feel aggressive. This high level of roundedness (1rem/16px minimum for standard elements) reinforces the community-focused and whimsical personality. Larger containers and cards should use the `rounded-xl` (3rem/48px) token to create a "soft bubble" effect that feels safe and welcoming.

## Components
Consistent component styling is vital for maintaining the energetic brand voice:

- **Buttons:** Use fully rounded (pill) shapes. Primary buttons use the high-saturation Green with white text. Secondary buttons should use a soft tinted background of the Primary Green at 10% opacity with Green text.
- **Cards:** Cards should have no borders; instead, use a subtle "Surface" white against the warm background with a 10% opacity tinted shadow.
- **Input Fields:** Use a subtle 1px stroke in a light neutral, which thickens and changes to the Primary Green on focus.
- **Chips & Tags:** Use highly vibrant backgrounds with 15% opacity and high-contrast text for a "gem-like" appearance.
- **Lists:** Use custom "leaf" or "circle" icons for bullets to continue the organic theme.
- **Checkboxes:** When checked, they should "bloom"—using a scale-up animation and the Primary Green fill.