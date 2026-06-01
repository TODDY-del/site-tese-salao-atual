---
name: Ethos of Elegance
colors:
  surface: '#fcf9f5'
  surface-dim: '#dcdad6'
  surface-bright: '#fcf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ef'
  surface-container: '#f0ede9'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e5e2de'
  on-surface: '#1c1c1a'
  on-surface-variant: '#4c4546'
  inverse-surface: '#31302e'
  inverse-on-surface: '#f3f0ec'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2e1506'
  on-tertiary-container: '#a47b65'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ecbda4'
  on-tertiary-fixed: '#2e1506'
  on-tertiary-fixed-variant: '#603f2d'
  background: '#fcf9f5'
  on-background: '#1c1c1a'
  surface-variant: '#e5e2de'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
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
  section-padding: 120px
  stack-sm: 16px
  stack-md: 32px
---

## Brand & Style
The design system is rooted in the "Editorial Spa" aesthetic—a fusion of high-fashion magazine layouts and the serene, restorative atmosphere of a luxury wellness retreat. The brand personality is poised, sophisticated, and welcoming, targeting a high-end clientele that values both meticulous professionalism and aesthetic grace. 

The visual style utilizes a refined **Minimalism** layered with **Organic Softness**. It prioritizes extreme "airy" whitespace to allow imagery and typography to breathe, mimicking the quietude of a sanctuary. This is punctuated by flowing shapes and subtle botanical motifs that soften the grid, ensuring the interface feels human and curated rather than clinical.

## Colors
This design system employs a high-contrast foundation of Black and White to anchor the brand's logo and professional authority. This monochromatic base is softened by a sophisticated palette of warm, skin-toned neutrals and metallic accents.

- **Primary (Black):** Used exclusively for the logo, primary headings, and high-priority CTAs to maintain a sense of "Editorial" authority.
- **Secondary (Champagne Gold):** Applied sparingly for interactive highlights, icons, and subtle decorative borders.
- **Tertiary (Dusty Rose/Blush):** Used for soft backgrounds, hover states, and to instill a sense of femininity and warmth.
- **Neutral (Warm Ivory):** The primary canvas color, used instead of pure white to provide a softer, more premium "paper" feel.

## Typography
The typography is a deliberate pairing of intellectual tradition and modern clarity. 

**Headings** utilize **Noto Serif**, chosen for its timeless, editorial character. Large display styles should feature light weights and tight letter-spacing to mimic fashion mastheads. **Body text** utilizes **Manrope**, a refined sans-serif that ensures high readability and a clean, contemporary feel. **Labels and small UI elements** use uppercase Manrope with increased tracking to create a sense of premium "branding" on even the smallest functional components.

## Layout & Spacing
The layout follows a **Fixed Grid** model within a generous max-width container, emphasizing a structured, magazine-like composition. 

Key layout principles:
- **Asymmetrical Balance:** Use offset columns and varied image aspect ratios to create visual interest.
- **Extreme Margins:** Section vertical padding is intentionally large (120px+) to isolate content and reduce cognitive load.
- **Sticky Navigation:** A slim, semi-transparent ivory bar persists at the top, housing the logo and a prominent "Book Now" CTA.
- **White Space as a Feature:** Negative space is not "empty" but is used as a luxury element to frame photography and services.

## Elevation & Depth
Depth is conveyed through **Ambient Shadows** and **Tonal Layering** rather than heavy 3D effects. 

Surfaces should feel light and lifted. Shadows are extra-diffused (large blur radius) with very low opacity, often tinted with a hint of the "Dusty Rose" tertiary color to maintain warmth. Backgrounds use "Warm Ivory," while foreground cards or modals use "Pure White," creating a subtle "layered paper" effect. Backdrop blurs (glassmorphism) are reserved strictly for the sticky navigation bar and high-end modal overlays to maintain the "Modern Spa" feel.

## Shapes
The shape language is defined by **Roundedness** and **Organic Curvature**. 

While the structural grid is disciplined, UI elements like buttons and cards feature 0.5rem to 1.5rem corner radii. Photography should occasionally utilize organic, non-geometric masks (e.g., pebble shapes or soft arches) to break the rigidity of the screen. Decorative elements include subtle botanical line art and flowing divider lines that guide the eye between sections.

## Components
- **Buttons:** Primary buttons are solid Black with White text, featuring a subtle hover shift to Champagne Gold. Secondary buttons use a fine Gold border with a transparent background (Ghost style).
- **Sticky Navigation:** A 72px tall bar with an ivory background (90% opacity) and a delicate bottom border.
- **Service Cards:** Minimalist tiles with a focus on high-quality imagery. Text is centered below the image using Noto Serif for the service title.
- **Booking CTA:** A distinct, high-contrast button present in the navigation and at the end of every page section.
- **Input Fields:** Bottom-border only (underlined style) to maintain an elegant, editorial look, using Manrope for placeholder text.
- **Botanical Accents:** Small, SVG-based leaf or floral silhouettes used as corner decorations or section breaks, rendered in a very faint Dusty Rose.