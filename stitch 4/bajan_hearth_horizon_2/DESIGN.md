---
name: Bajan Hearth & Horizon
colors:
  surface: '#fff8f6'
  surface-dim: '#fbd1c4'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ed'
  surface-container: '#ffe9e3'
  surface-container-high: '#ffe2da'
  surface-container-highest: '#ffdbd0'
  on-surface: '#2c160e'
  on-surface-variant: '#504442'
  inverse-surface: '#442a22'
  inverse-on-surface: '#ffede8'
  outline: '#827472'
  outline-variant: '#d3c3c0'
  surface-tint: '#745853'
  primary: '#271310'
  on-primary: '#ffffff'
  primary-container: '#3e2723'
  on-primary-container: '#ae8d87'
  inverse-primary: '#e3beb8'
  secondary: '#635e53'
  on-secondary: '#ffffff'
  secondary-container: '#e9e2d3'
  on-secondary-container: '#696458'
  tertiary: '#271400'
  on-tertiary: '#ffffff'
  tertiary-container: '#432600'
  on-tertiary-container: '#c0894a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#e3beb8'
  on-primary-fixed: '#2b1613'
  on-primary-fixed-variant: '#5b403c'
  secondary-fixed: '#e9e2d3'
  secondary-fixed-dim: '#cdc6b8'
  on-secondary-fixed: '#1e1b13'
  on-secondary-fixed-variant: '#4b463c'
  tertiary-fixed: '#ffdcbb'
  tertiary-fixed-dim: '#f9ba77'
  on-tertiary-fixed: '#2c1700'
  on-tertiary-fixed-variant: '#673d02'
  background: '#fff8f6'
  on-background: '#2c160e'
  surface-variant: '#ffdbd0'
typography:
  display-xl:
    fontFamily: Newsreader
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
  headline-md:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
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
  container-max: 1280px
  gutter: 24px
  margin: 32px
  section-padding: 80px
---

## Brand & Style
This design system captures the soulful essence of Barbadian heritage through a lens of contemporary luxury. It is built to evoke the warmth of a morning kitchen and the steady reliability of a multi-generational legacy. The brand personality is "The Sophisticated Storyteller"—rooted in community, yet refined enough for a global stage.

The aesthetic leans into a **Modern Tactile** style. It rejects the coldness of standard digital interfaces in favor of soft, paper-like surfaces and matte finishes. By combining high-fidelity layouts with organic, heritage-inspired textures, the UI creates an emotional response of comfort, quality, and belonging. It prioritizes generous whitespace and a "slow-design" philosophy that encourages users to savor the experience, much like a traditional Bajan pastry.

## Colors
The palette is an homage to the textures of a Bajan bakery: the deep, matte molasses of charred wood and dark chocolate, contrasted against the airy softness of unbleached flour and coastal sands.

- **Primary (Molasses):** A deep, matte brown used for typography and structural elements to provide grounding and authority.
- **Secondary (Clutch Cream):** The foundation of the UI, replacing harsh whites with a warm, inviting canvas that feels like premium stationery.
- **Tertiary (Golden Crust):** An accent color used sparingly for calls to action and highlights, reflecting the perfect bake on a salt bread or turnover.
- **Neutral (Hearth Ash):** Muted browns used for secondary text and decorative borders to maintain warmth without competing with the primary hierarchy.

## Typography
The typographic strategy balances editorial elegance with approachable modernism. 

**Newsreader** is utilized for headlines to instill a sense of literary tradition and "High Bajan" heritage. Its classic serif terminals provide the "Horizon" element—aspirational and timeless.

**Be Vietnam Pro** handles all functional and body text. Its friendly, contemporary construction ensures that the design system remains welcoming and easy to navigate across digital platforms. This combination ensures that while the brand feels premium, it never feels inaccessible or "cold." All labels should be set with a slight tracking increase to maintain legibility against matte backgrounds.

## Layout & Spacing
The design system employs a **Fixed Grid** model to maintain an editorial, high-fidelity feel that mimics a luxury cookbook or magazine. 

A 12-column grid is used for desktop layouts, with generous 32px outer margins to "frame" the content, making the UI feel like a curated gallery. Vertical rhythm is strictly governed by an 8px base unit. For high-impact brand moments, utilize "Section Padding" (80px+) to allow the heritage-focused imagery and typography to breathe, reinforcing the premium nature of the product.

## Elevation & Depth
This design system avoids harsh dropshadows or heavy skeuomorphism. Instead, depth is communicated through **Tonal Layers** and **Ambient Shadows**.

Surfaces use extremely soft, diffused shadows with a slight brown tint (`rgba(62, 39, 35, 0.08)`) to mimic the way light hits a matte, organic object. Backgrounds should use subtle grain textures or "flour-dust" overlays to prevent the cream surfaces from feeling flat. When an element is raised, it doesn't just "glow"; it gains a very thin, low-contrast inner stroke to simulate the physical edge of thick-cut cardstock.

## Shapes
The shape language is organic yet disciplined. A "Rounded" (0.5rem) base is applied to most UI components to reflect the hand-molded nature of artisanal baking. 

Larger containers like cards or featured sections use `rounded-lg` (1rem) to soften the overall composition. Buttons should remain consistent at the base roundedness to feel sturdy and intentional. Circles are used exclusively for avatars or secondary decorative badges to contrast against the predominantly rectangular, grid-aligned layout.

## Components
### Buttons
Primary buttons are solid "Molasses" with "Clutch Cream" text, utilizing a matte finish. They should feel substantial—high padding and bold labeling. Secondary buttons use a "Golden Crust" outline with no fill, emphasizing a lighter touch.

### Cards
Cards are the primary storytelling vehicle. They should feature a very subtle 1px border in a slightly darker cream than the background, with a soft ambient shadow on hover. Use image-masking with organic, slightly irregular edges to emphasize the "Hearth" theme.

### Input Fields
Fields should use a "floating label" style with a bottom-only border or a very light tonal fill. Focus states should transition the border to the primary brown with a soft, warm glow.

### Chips & Tags
Chips represent flavors or categories. These should use the Tertiary color at 10% opacity with 100% opacity text, creating a soft, highlighted effect that doesn't distract from the primary content.

### Specialty Components: "The Heritage Banner"
A unique component for this design system, featuring a full-width section with a subtle parchment texture, used for community stories or bakery history, anchored by a "Newsreader" display headline.