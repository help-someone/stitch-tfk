---
name: Artisanal Warmth
colors:
  surface: '#faf9f6'
  surface-dim: '#dadad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f0'
  surface-container: '#efeeea'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2df'
  on-surface: '#1a1c1a'
  on-surface-variant: '#424842'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f1f1ed'
  outline: '#737972'
  outline-variant: '#c2c8c0'
  surface-tint: '#4a654f'
  primary: '#4a654f'
  on-primary: '#ffffff'
  primary-container: '#8daa91'
  on-primary-container: '#253f2b'
  inverse-primary: '#b0ceb4'
  secondary: '#695e3d'
  on-secondary: '#ffffff'
  secondary-container: '#eedfb5'
  on-secondary-container: '#6d6241'
  tertiary: '#745944'
  on-tertiary: '#ffffff'
  tertiary-container: '#bd9d84'
  on-tertiary-container: '#4b3521'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cceacf'
  primary-fixed-dim: '#b0ceb4'
  on-primary-fixed: '#062010'
  on-primary-fixed-variant: '#334d38'
  secondary-fixed: '#f1e1b8'
  secondary-fixed-dim: '#d5c69d'
  on-secondary-fixed: '#221b02'
  on-secondary-fixed-variant: '#504627'
  tertiary-fixed: '#ffdcc2'
  tertiary-fixed-dim: '#e3c0a6'
  on-tertiary-fixed: '#2a1707'
  on-tertiary-fixed-variant: '#5a422e'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2df'
typography:
  display-lg:
    fontFamily: beVietnamPro
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: beVietnamPro
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: beVietnamPro
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: plusJakartaSans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

This design system is built on the philosophy of "Soft Minimalism"—a blend of modern digital clarity and the tactile, imperfect charm of handmade crafts. The brand personality is intimate, cozy, and nurturing, aiming to evoke the emotional warmth of receiving a hand-knitted gift. 

The aesthetic leverages a Tactile Minimalist approach. It prioritizes generous white space and clean layouts to ensure the intricate textures of crochet work remain the focal point. However, unlike traditional cold minimalism, this system introduces "human" elements through organic shapes, soft-focus photography, and a color palette that feels like sun-drenched wool. The goal is to create a digital environment that feels as soft and approachable as the physical products themselves.

## Colors

The palette is inspired by natural fibers and botanical dyes. The primary green acts as a grounding, organic anchor, while the yellow and peach highlights function as "warm sunlight," used for calls to action and celebratory UI moments. 

In light mode, the cream background provides a softer, more eye-friendly alternative to pure white, mimicking unbleached cotton. The dark mode shifts to a muted charcoal (rather than pure black) to maintain a soft, low-contrast experience that preserves the "pastels at twilight" aesthetic. Neutral tones should always lean warm to avoid a clinical feel.

## Typography

The typography strategy balances playfulness with legibility. Headings utilize **beVietnamPro**, chosen for its contemporary yet friendly curves that echo the loops of a crochet stitch. It should be used with slightly tighter letter-spacing in large formats to create a "hugged" appearance.

For all functional and long-form text, **Plus Jakarta Sans** provides a modern, geometric clarity. Its naturally wide apertures and rounded terminals maintain the system's "soft" requirement while ensuring maximum readability across mobile and desktop interfaces. Line heights are intentionally generous (1.6x) to contribute to the airy, stress-free layout.

## Layout & Spacing

This design system employs a fluid-to-fixed grid hybrid based on an 8px spacing scale. To reinforce the sense of "breathing room," internal component padding should lean toward the larger end of the scale (e.g., using 24px or 32px instead of 16px).

The layout philosophy is "Centered and Grounded." Content should be contained within a maximum width of 1200px to prevent visual strain. Margins are intentionally wide to create a frame-like effect around products, treating every crochet piece like a work of art in a gallery. Use asymmetric spacing occasionally to mimic the organic, non-linear nature of handmade goods.

## Elevation & Depth

Depth in this system is achieved through **Ambient Shadows** and **Tonal Layers** rather than harsh borders. 

1. **Shadow Character:** Shadows must be extremely diffused (large blur radius) and low opacity. Use a slight tint of the primary green or peach in the shadow color (e.g., #8DAA91 at 8% opacity) instead of pure gray to maintain the warm, emotional tone.
2. **Layering:** Surfaces should feel like they are "resting" on one another. Use the cream background as the base, and slightly lighter or warmer surfaces for elevated cards. 
3. **Transitions:** All hover and active states must use "ease-out-cubic" or "soft-spring" transitions to create a sense of physical weight and responsiveness that feels human rather than mechanical.

## Shapes

The shape language is dominated by high-radius curves. There are no sharp corners in this design system. 

- **Primary Radius:** Used for cards and containers, providing a friendly, safe appearance.
- **Secondary Radius (Large):** Used for buttons and chips to create a "squishy" or pill-like aesthetic.
- **Organic Accents:** Icons and decorative elements should favor hand-drawn, slightly irregular circles or blobs to emphasize the "handcrafted" nature of the brand.

## Components

### Buttons
Primary buttons are pill-shaped and utilize the pastel green background with dark text. They should have a subtle "lift" effect on hover using an ambient shadow. Secondary buttons use a thick 2px stroke in the peach accent color with a transparent background.

### Cards
Cards are the primary vehicle for product displays. They feature 1rem rounded corners, a very soft tinted shadow, and no border. The background of the card should be a slightly different shade (e.g., a lighter cream or a very soft peach) than the main page background to create a "layered" effect.

### Input Fields
Inputs should use a soft-filled style rather than a border-only style. The background should be a subtle 5% tint of the primary color. On focus, the background transitions to white with a soft, glowing peach shadow.

### Chips & Tags
Used for material types (e.g., "100% Cotton"). These should be fully rounded (pill) with low-saturation pastel backgrounds. Use small, playful icons next to the text where possible.

### Interactive Micro-interactions
Checkboxes and radio buttons should feel "bouncy." When selected, they should perform a subtle scale-up and scale-down animation, mimicking the elasticity of yarn.