---
name: Bajan Hearth & Horizon
colors:
  surface: '#fff8f6'
  surface-dim: '#e0d8d6'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2ef'
  surface-container: '#f4ecea'
  surface-container-high: '#efe6e4'
  surface-container-highest: '#e9e1de'
  on-surface: '#1e1b1a'
  on-surface-variant: '#504440'
  inverse-surface: '#33302e'
  inverse-on-surface: '#f7efec'
  outline: '#82746f'
  outline-variant: '#d4c3bd'
  surface-tint: '#765749'
  primary: '#432a1e'
  on-primary: '#ffffff'
  primary-container: '#5c4033'
  on-primary-container: '#d3ac9c'
  inverse-primary: '#e6bead'
  secondary: '#805533'
  on-secondary: '#ffffff'
  secondary-container: '#fdc39a'
  on-secondary-container: '#794e2e'
  tertiary: '#1b3434'
  on-tertiary: '#ffffff'
  tertiary-container: '#324b4b'
  on-tertiary-container: '#9fbaba'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#e6bead'
  on-primary-fixed: '#2c160b'
  on-primary-fixed-variant: '#5c4033'
  secondary-fixed: '#ffdcc5'
  secondary-fixed-dim: '#f4bb92'
  on-secondary-fixed: '#301400'
  on-secondary-fixed-variant: '#653d1e'
  tertiary-fixed: '#cce8e7'
  tertiary-fixed-dim: '#b0cccb'
  on-tertiary-fixed: '#051f20'
  on-tertiary-fixed-variant: '#324b4b'
  background: '#fff8f6'
  on-background: '#1e1b1a'
  surface-variant: '#e9e1de'
typography:
  display-lg:
    fontFamily: plusJakartaSans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: plusJakartaSans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: plusJakartaSans
    fontSize: 32px
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
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  max-width: 1440px
---

## Brand & Style

This design system captures the essence of a heritage Barbadian bakery through a lens of modern, weightless digital experiences. It balances the grounded, earthy reliability of wholesale baking with a premium, immersive retail experience. 

The aesthetic is a fusion of **Tactile Minimalism** and **Google Antigravity**. Elements do not sit heavily on the page; they float in a soft, atmospheric space, suggesting the lightness of rising dough and the warmth of a Caribbean breeze. Motion is used to reinforce this sense of "levitation," utilizing subtle parallax and staggered scroll reveals to create a premium, rhythmic flow that mirrors the artisanal process.

## Colors

The palette is derived from the natural materials of the bakery: toasted crusts, rich earth, and golden grains. 

- **Primary & Secondary Browns** provide the "baked" foundation, used for structural elements and high-contrast text.
- **Burnt Orange** acts as a kinetic accent, used sparingly for calls to action and to highlight the warmth of the Bajan sun.
- **Cream & Soft Tan** form the atmospheric backdrop, replacing stark white with a softer, organic tone that reduces eye strain and enhances the premium feel.

## Typography

The system utilizes **Plus Jakarta Sans** (as a high-quality alternative to Poppins/Figtree that maintains a modern, rounded, and friendly Bajan warmth). 

Headlines are bold and authoritative but softened by the typeface's geometric curves. Body text remains highly legible with generous line heights to accommodate the immersive, airy layout. Large display sizes should be used for product titles to create a "magazine" feel, while labels utilize uppercase styling for a sophisticated, wholesale-tag aesthetic.

## Layout & Spacing

This design system uses a **Fluid Antigravity Grid**. While structural elements align to a standard 12-column grid, individual floating components (like product cards and imagery) are intentionally offset by 8px–16px from the baseline to create a "shimmering" effect during scroll.

Spacing is expansive. Whitespace is treated as "air" to let the product photography breathe. Large vertical padding (120px+) between sections is encouraged to facilitate smooth scroll-triggered animations.

## Elevation & Depth

To achieve the "Antigravity" style, the system avoids traditional hard shadows. Instead, it uses **Ambient Tonal Depth**:

1.  **Floating Layers:** Elements use very large, ultra-soft shadows tinted with the primary brown (#5C4033 at 5% opacity) to suggest they are hovering 20-40px above the cream surface.
2.  **Parallax Offsets:** Background elements move at 0.5x speed, while foreground product cards move at 1.1x speed, creating physical depth without heavy gradients.
3.  **Backdrop Blurs:** The sticky header uses a `blur(12px)` effect on the Soft Tan background to maintain legibility while preserving the sense of spatial continuity.

## Shapes

The shape language is organic and approachable. Sharp corners are avoided to mirror the soft forms of fresh bread. 

- **Standard Containers:** Use a 16px (1rem) radius.
- **Interactive Elements:** Buttons and tags use a fully pill-shaped (32px+) radius to encourage touch and interaction.
- **Product Imagery:** Uses a mix of soft-rounded rectangles and occasional "organic blobs" to break the rigidity of the grid.

## Components

### Global Header & Footer
- **Header:** Transparent on hero entry; transitions to a semi-transparent Soft Tan (#EDE0D4) with a backdrop blur upon scroll. Navigation links use Burnt Orange for hover states.
- **Footer:** Immersive "Earthy" block using Deep Brown (#5C4033) background with Cream text. Includes a large-scale logo and social icons.

### Floating Product & Recipe Cards
- Elevated containers with a 16px radius. 
- Images should bleed to the top and sides, with product details resting in a padded area below. 
- On hover, cards should "lift" (scale 1.05x) and increase shadow spread.

### Responsive Forms & Newsletter
- **Inputs:** Soft Tan background with a subtle Deep Brown bottom border. 
- **Newsletter Widget:** A floating "toast-style" or centered card with a Burnt Orange button.
- **Buttons:** High-contrast Burnt Orange (#D2691E) with white text.

### Testimonial Carousels
- Center-aligned typography with large, decorative Burnt Orange quotation marks. 
- Smooth horizontal transition with "physics-based" dragging for mobile users.

### Recipe Cards
- Split layout: High-quality food photography on one side, clean Figtree-driven typography on the other. 
- Includes "Bajan Legend" icons for local flavor/ingredients.