---
name: Bajan Hearth & Horizon
colors:
  surface: '#fcf8f8'
  surface-dim: '#ddd9d9'
  surface-bright: '#fcf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c8'
  surface-tint: '#5d5f5f'
  primary: '#5d5f5f'
  on-primary: '#ffffff'
  primary-container: '#ffffff'
  on-primary-container: '#747676'
  inverse-primary: '#c6c6c7'
  secondary: '#6d5b4e'
  on-secondary: '#ffffff'
  secondary-container: '#f4dbcb'
  on-secondary-container: '#715f52'
  tertiary: '#695c53'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffffff'
  on-tertiary-container: '#817369'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#f6dece'
  secondary-fixed-dim: '#d9c2b3'
  on-secondary-fixed: '#25190f'
  on-secondary-fixed-variant: '#544438'
  tertiary-fixed: '#f1dfd3'
  tertiary-fixed-dim: '#d4c3b8'
  on-tertiary-fixed: '#231a13'
  on-tertiary-fixed-variant: '#50453c'
  background: '#fcf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Newsreader
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Newsreader
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Newsreader
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1.2'
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
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is built upon the intersection of Bajan heritage and modern artisan baking. The brand personality is grounded, archival, and premium, evoking the warmth of a communal hearth through a sophisticated, editorial lens. 

The style utilizes **Minimalism** with **Tactile** influences. By stripping away high-saturation colors and unnecessary decorative elements, the focus shifts to the quality of the craft and the texture of the products. The visual language should feel "matte"—avoiding gloss, vibrant gradients, or digital-first neon hues—to mirror the organic nature of flour, wood, and earth. The interface should feel like a high-end culinary journal: spacious, authoritative, and deeply inviting.

## Colors

The palette is rooted in a monochromatic white foundation to ensure a clean, modern atmosphere. Secondary tones are derived from the baking process and the Bajan landscape: 
- **Roasted Bean (#433429):** A deep, matte brown used for primary text and core brand elements.
- **Silt (#8C7E74):** A desaturated earthy mid-tone for secondary UI elements and borders.
- **Oatmeal (#F9F7F5):** A warm cream used for container backgrounds to provide soft contrast against the white base.
- **Raw Canvas (#D9C5B2):** A muted accent for interactive states and highlights.

All colors are intentionally low-saturation to maintain a matte, sophisticated aesthetic that does not compete with food photography.

## Typography

This design system exclusively utilizes **Newsreader** to establish a literary, heritage-driven feel. This serif choice brings an air of traditional craftsmanship and storytelling to the digital space. 

Headlines should use tighter letter-spacing and slightly heavier weights to command attention, while body text remains spacious with a generous line height for maximum readability and a premium feel. Labels are set in a smaller, semi-bold weight with increased letter-spacing and uppercase styling to provide a clear functional distinction from editorial content without introducing a second typeface.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop experiences to maintain the "contained" feel of a printed book or menu. A 12-column grid is used with generous 24px gutters.

Spacing is strictly based on an 8px rhythm. Large-scale white space is encouraged between sections (using `xl` spacing) to evoke a sense of luxury and calm. Content should be centered with wide horizontal margins, ensuring that the focal point remains the bakery’s products and community stories.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layers** rather than traditional shadows. To maintain the matte aesthetic, UI elements are differentiated by color shifts between White (#FFFFFF) and Oatmeal (#F9F7F5).

Where physical separation is required, use **Low-contrast outlines** in Silt (#8C7E74) at a very low opacity (10-15%). If shadows are absolutely necessary for high-priority modals, they must be "ambient"—highly diffused, with no distinct light source, and tinted with the secondary brown to avoid a "grey" digital look.

## Shapes

The shape language reflects "Round Eight" logic, providing a soft, approachable feel that balances the sharp serifs of the typography. The standard radius is 0.5rem (8px), which is applied to all primary interactive elements. This level of roundness suggests hand-formed quality—neither too clinical nor too bubbly—fitting the artisan nature of Zephirin's Bakery.

## Components

### Buttons
Primary buttons use the Roasted Bean (#433429) background with White text. Secondary buttons use a Silt outline with no background. All buttons feature the standard 8px roundness and a subtle 1px matte border.

### Input Fields
Inputs are defined by a bottom-border only or a very light Oatmeal (#F9F7F5) background, emphasizing a clean, archival look. Focus states use a subtle 1px Silt outline.

### Cards
Cards are used to display bakery items or community stories. They should feature no shadows; instead, they use a subtle color fill (Oatmeal) or a 1px matte border to separate themselves from the white background.

### Chips & Tags
Used for dietary labels (e.g., "Vegan," "Local"). These are small, pill-shaped elements using the Silt color at 10% opacity with Roasted Bean text for a quiet, informative presence.

### Lists
Menu lists should be spaced generously with horizontal dividers that do not span the full width of the container, reinforcing the editorial, minimalist style.

### Heritage Accents
Use custom dividers inspired by traditional Bajan patterns or simple horizontal lines to separate editorial sections, keeping them desaturated and thin (1px).