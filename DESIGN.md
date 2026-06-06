---
name: Botanical Excellence
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1b1c1a'
  on-surface-variant: '#434843'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#737973'
  outline-variant: '#c3c8c1'
  surface-tint: '#4d6453'
  primary: '#061b0e'
  on-primary: '#ffffff'
  primary-container: '#1b3022'
  on-primary-container: '#819986'
  inverse-primary: '#b4cdb8'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#271013'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f2427'
  on-tertiary-container: '#b0898c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9d4'
  primary-fixed-dim: '#b4cdb8'
  on-primary-fixed: '#0b2013'
  on-primary-fixed-variant: '#364c3c'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#e7bcbf'
  on-tertiary-fixed: '#2d1417'
  on-tertiary-fixed-variant: '#5d3f42'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 60px
  section-gap: 120px
---

## Brand & Style

This design system establishes a high-end, eco-conscious identity that bridges the gap between traditional herbal wisdom and modern luxury. The aesthetic is rooted in **Premium Minimalism** with a **Tactile** twist, drawing heavy inspiration from high-end apothecary branding and Apple-style interface clarity.

The interface should evoke a sense of calm, purity, and scientific precision. By blending generous whitespace with rich, organic textures—such as high-resolution leaf macros and soft paper textures—the UI creates a multisensory experience. Glassmorphism is used sparingly to represent the transparency of the oils and the purity of the brand’s extraction processes.

**Visual Principles:**
- **Purity through Space:** Use excessive whitespace to frame products like art pieces.
- **Organic Precision:** Combine perfectly geometric layouts with soft, botanical imagery.
- **Glass & Light:** Use translucent layers to create depth without clutter, mimicking the look of frosted glass bottles.

## Colors

The palette is a sophisticated "Herbal-Neutral" scheme. The **Deep Herbal Green** acts as the anchor, providing a foundation of growth and stability. The **Golden Amber** is used strictly for high-value interactions and "premium" signifiers, mimicking the liquid gold appearance of high-quality oil.

**Application Rules:**
- **Primary Green:** Used for headers, primary buttons, and heavy structural elements.
- **Golden Amber:** Reserved for price points, ratings, "Add to Cart" accents, and luxury seals.
- **Cream Background:** This replaces pure white to reduce eye strain and provide a warmer, more "recycled paper" or "organic linen" feel.
- **Sage & White:** Used for secondary backgrounds and card surfaces to create a soft layered effect.

## Typography

The typography system relies on a high-contrast pairing. **Playfair Display** provides the editorial, "Vogue-esque" authority required for a luxury brand. Its serifs are sharp and elegant, suggesting heritage and quality.

**Montserrat** provides a clean, geometric counterpoint for functional text. The increased line-height in body copy ensures the reading experience is relaxed and accessible, mirroring the "wellness" nature of the product. Use uppercase for labels and small buttons to add a sense of modern architectural structure to the layout.

## Layout & Spacing

This design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. The layout philosophy is "Centrally Weighted," meaning key content is often centered with expansive horizontal margins to create a boutique feel.

**Spatial Rhythm:**
- **Verticality:** Use large 120px gaps between major sections to allow the design to "breathe."
- **Nesting:** Elements inside cards should use a 32px padding to maintain the "premium" airy feel.
- **Responsibility:** On mobile, margins reduce to 20px, but vertical section gaps should remain relatively high (80px) to prevent the mobile experience from feeling cramped.

## Elevation & Depth

Depth is achieved through **Soft Layering** rather than traditional heavy shadows.

1.  **Level 0 (Base):** The Cream (#F5F5DC) background.
2.  **Level 1 (Cards):** Soft Sage or White surfaces with a very subtle 1px border (#1B3022 at 5% opacity) and a long, diffused "Ambient" shadow (0 10px 30px rgba(27, 48, 34, 0.04)).
3.  **Level 2 (Overlays/Glass):** Used for navigation bars and modal windows. A backdrop-blur of 20px combined with a 60% opacity white fill creates the signature glass effect.
4.  **Floating Elements:** Elements like "Floating Action Buttons" use a slightly more pronounced shadow to indicate interactivity.

## Shapes

The shape language is defined by **Large, Soft Radii**. Square corners are avoided entirely to maintain the "organic" and "natural" brand promise.

- **Standard Elements:** Buttons and input fields use a 0.5rem (8px) radius.
- **Containers:** Product cards and testimonial blocks use a "rounded-xl" (1.5rem / 24px) radius to create a soft, friendly silhouette.
- **Images:** Product photography should always feature slightly rounded corners (1rem) to integrate seamlessly with the UI.

## Components

### Buttons
- **Primary:** Solid Deep Herbal Green, White text. No border. On hover, the color shifts slightly toward Sage.
- **Secondary:** Transparent with a 1.5px Green border.
- **Luxury/CTA:** Golden Amber background with Charcoal text. Use this only for the "Complete Purchase" or "Subscribe" actions.

### Cards
Cards are the primary content vessel. Use the **Glassmorphism** style for featured product categories. A card should have a 1px inner stroke of white at 20% to simulate a glass edge.

### Inputs
Search bars and form fields should be "Ghost" style: Cream background slightly darker than the page background, with a soft Sage focus ring.

### Botanical Accents
Include a "Floating Leaf" component—a decorative, low-opacity SVG leaf that can be placed behind cards or in the corners of sections to reinforce the herbal theme without interfering with legibility.

### Progress & Loading
Loading states should use a slow, pulsing Golden Amber "oil drop" animation to maintain brand immersion.