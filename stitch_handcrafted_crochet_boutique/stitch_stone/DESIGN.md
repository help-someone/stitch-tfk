---
name: Stitch & Stone
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
  secondary: '#715c00'
  on-secondary: '#ffffff'
  secondary-container: '#ffdd67'
  on-secondary-container: '#766100'
  tertiary: '#6f5a48'
  on-tertiary: '#ffffff'
  tertiary-container: '#b89e88'
  on-tertiary-container: '#473625'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cceacf'
  primary-fixed-dim: '#b0ceb4'
  on-primary-fixed: '#062010'
  on-primary-fixed-variant: '#334d38'
  secondary-fixed: '#ffe17a'
  secondary-fixed-dim: '#e4c451'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#554500'
  tertiary-fixed: '#faddc5'
  tertiary-fixed-dim: '#ddc2aa'
  on-tertiary-fixed: '#27180a'
  on-tertiary-fixed-variant: '#564332'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2df'
typography:
  h1:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
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
  label-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 80px
  grid-margin: 24px
  grid-gutter: 16px
  container-max: 1280px
---

## Brand & Style

The design system is built to reflect the slow, intentional process of hand-crocheted art. It targets a discerning audience that values craftsmanship, sustainability, and personal touch. The aesthetic is "Warm Minimalism"—it strips away the clutter of traditional e-commerce while retaining the tactile warmth of a boutique. 

The visual style blends **Soft UI** with **Minimalism**. It uses generous whitespace to let product photography breathe, paired with a color palette that feels organic and sun-bleached. Every interaction is designed to feel "cushioned," avoiding sharp edges or jarring transitions to mimic the softness of yarn and fiber.

## Colors

The primary palette is rooted in nature. The sage green provides a grounding, professional accent, while honey yellow and soft peach offer highlights of warmth and joy. 

In light mode, the background uses a soft cream rather than a clinical white to reduce eye strain and feel more like unbleached cotton. Dark mode shifts to a charcoal canvas, utilizing muted pastel versions of the brand colors to maintain the "handcrafted" feel without harsh contrast. Primary accents should be used for calls to action, while secondary and tertiary tones are reserved for decorative elements, chip backgrounds, and category signifiers.

## Typography

This design system utilizes a tiered typographic approach to balance personality with utility. **Plus Jakarta Sans** serves as the heading font; its slightly rounded terminals and geometric clarity feel friendly yet structured. Headings should use tight letter spacing to feel modern and "editorial."

**Inter** is the workhorse for body text and functional UI. It ensures high legibility for product descriptions and checkout flows. Labels and small metadata should be set in Inter with increased letter-spacing and uppercase styling to create a clean, organized shop hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop, centering the content with a maximum width of 1280px to maintain the "boutique shop" feel. On mobile and tablet, it transitions to a fluid model with consistent 24px side margins.

The spacing rhythm is airy and generous. Section gaps are intentionally large (80px+) to prevent the user from feeling rushed through the experience. Product grids should utilize an asymmetrical layout or plenty of "dead space" around images to mimic the curated display of an art gallery.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and tonal layering. Rather than traditional heavy shadows, this design system uses soft, wide-spread blurs with a slight tint of the primary Sage color to create a "lifted" effect.

Surfaces use subtle tonal shifts. For instance, a product card may have a slightly different cream tint than the main background. All transitions—hovering over a button or opening a menu—must use a ease-in-out timing function (approx 300ms) to ensure the UI feels fluid and organic, never mechanical.

## Shapes

The shape language is consistently **Rounded**. Hard corners are non-existent in the design system, reflecting the looped and curved nature of crochet stitching. 

Buttons, input fields, and small containers use a 0.5rem (8px) radius. Larger components like product cards or hero banners utilize a 1.5rem (24px) radius to create a soft, inviting frame for content. Images should always be clipped with the same radius as their parent container to maintain visual harmony.

## Components

### Buttons
Buttons are minimal, using the Sage Green for primary actions. Hover states involve a subtle scale increase (1.02x) and a deepening of the ambient shadow rather than a dramatic color shift. Secondary buttons should be ghost-style with a thin sage border and soft cream background.

### Product Cards
Cards are borderless, relying on the soft shadow and whitespace for definition. On hover, the product image should feature a subtle, slow zoom-in effect. Pricing is displayed in a clean, high-contrast label font below the image.

### Navigation
The sticky navigation bar uses a high-blur backdrop filter (glassmorphism) over the cream background color. This ensures content remains legible as it scrolls underneath while maintaining the light, airy feel.

### Input Fields & Selects
Inputs are soft-rounded with a subtle #F9DCC4 (Peach) border when focused, creating a warm, non-aggressive interactive state.

### Chips/Tags
Used for "In Stock" or "New" labels, these should be pill-shaped with low-saturation backgrounds of the secondary honey yellow or peach colors.