---
name: LỤA BẠC Design System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#454843'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#757873'
  outline-variant: '#c5c7c1'
  surface-tint: '#5d5f5b'
  primary: '#5d5f5b'
  on-primary: '#ffffff'
  primary-container: '#f5f5f0'
  on-primary-container: '#6f706c'
  inverse-primary: '#c6c7c2'
  secondary: '#5c5f61'
  on-secondary: '#ffffff'
  secondary-container: '#dee0e2'
  on-secondary-container: '#606365'
  tertiary: '#5a5f64'
  on-tertiary: '#ffffff'
  tertiary-container: '#f1f5fb'
  on-tertiary-container: '#6b7075'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3e3de'
  primary-fixed-dim: '#c6c7c2'
  on-primary-fixed: '#1a1c19'
  on-primary-fixed-variant: '#454744'
  secondary-fixed: '#e1e3e5'
  secondary-fixed-dim: '#c4c7c9'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#444749'
  tertiary-fixed: '#dfe3e9'
  tertiary-fixed-dim: '#c3c7cd'
  on-tertiary-fixed: '#171c20'
  on-tertiary-fixed-variant: '#43474c'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: DM Sans
    fontSize: 48px
    fontWeight: '300'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: DM Sans
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
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
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

The design system embodies the essence of "Soft as Silk – Elegant as Silver." It targets a high-end audience seeking artisanal silver jewelry, demanding a digital experience that feels as curated and refined as a physical boutique.

The aesthetic is **Artisanal Minimalism**. It merges the clean lines of modern luxury with a soft, feminine grace. By utilizing expansive whitespace and a "quiet luxury" approach, the UI allows the intricate details of the silver craftsmanship to remain the focal point. The emotional response is one of serenity, prestige, and tactile quality.

**Core Principles:**
- **Ethereal Lightness:** Every element should feel as though it is floating or gently resting, never heavy or forced.
- **Sensory Detail:** High-resolution imagery is paired with subtle silver accents to mimic the luster of the product.
- **Human Touch:** Despite the digital medium, the use of airy layouts and sophisticated type suggests a hand-crafted, bespoke origin.

## Colors

The palette is a monochromatic exploration of light, designed to emphasize the reflective quality of silver.

- **Primary (White Pastel/Light Beige):** Used for background surfaces and containers to provide a warmer, more organic feel than pure white.
- **Neutral (Pure White):** Reserved for high-light areas, product cards, and active states to create a subtle "pop" against the beige backdrop.
- **Metallic Silver Accents:** Expressed through #E5E7E9 and #D1D5DB. These are not flat colors but should be used for fine lines, dividers, and icon strokes to simulate metal.
- **Typography/Ink:** A deep charcoal-grey (near black) is used for text to ensure readability while maintaining a softer contrast than true black.

**Application:** Use subtle linear gradients (0deg, #F9FAFB to #E5E7E9) on primary buttons to create a brushed-metal finish.

## Typography

The typography system relies on "Airy Spacing" and premium geometric sans-serifs to convey modern luxury.

- **Headlines:** Use **DM Sans** with light weights (300/400). The slight geometric nature feels architectural and precise, mirroring jewelry design.
- **Body & UI:** **Hanken Grotesk** provides exceptional readability with a contemporary, sharp finish. 
- **Character:** Headlines should favor increased letter-spacing (tracking) for a more "editorial" and expensive feel. All-caps labels are used sparingly for navigation and metadata to establish a clear hierarchy without increasing weight.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** model. Content is contained within a 1280px max-width to maintain an editorial feel on large displays, while internal margins remain generous to provide "breathability."

- **Generous Whitespace:** Section vertical padding is intentionally large (120px+) to separate different jewelry collections, preventing the UI from feeling cluttered or "discount."
- **Grid:** A 12-column grid is used for desktop. On mobile, a single-column flow is preferred for product storytelling, with 2-column grids reserved only for product listing pages.
- **Rhythm:** Spacing follows an 8px scale, but emphasizes larger increments (32px, 48px, 64px) to reinforce the minimalist aesthetic.

## Elevation & Depth

This design system avoids heavy drop shadows. Depth is created through **Tonal Layering** and **Subtle Luster**.

- **Surface Levels:** 
  - Level 0: Pure White (#FFFFFF) - Base background.
  - Level 1: Off-White/Beige (#F5F5F0) - Used for cards and inset sections.
- **Shadows:** When necessary (e.g., for modal overlays or floating navigation bars), use a "Silver Mist" shadow: a very high blur (40px+), very low opacity (3-5%) shadow with a slight blue-grey tint (#A3A3A3).
- **Glassmorphism:** Use high-diffusion backdrop blurs (20px) on navigation bars and quick-view overlays to maintain a sense of lightness and transparency, mimicking the way light passes through fine silk.

## Shapes

Shapes are defined by **Soft Geometric Fluidity**. 

- **Corners:** A base radius of 0.5rem (8px) is applied to most components, providing a modern but approachable feel. 
- **Buttons:** Primary buttons use a slightly higher radius (rounded-lg) or can be fully pill-shaped if the text label is short, emphasizing the "soft as silk" narrative.
- **Image Treatment:** Product photography should always use the `rounded-lg` (16px) or `rounded-xl` (24px) tokens to soften the visual impact of the frame.

## Components

### Buttons
- **Primary:** Background in a very light metallic gradient. Text in dark charcoal. No heavy borders.
- **Secondary/Ghost:** 1px stroke using the silver accent color (#D1D5DB). Transitions to a soft beige fill on hover.

### Cards (Product)
- No borders. Depth is indicated by a subtle change in background color (Level 1) or a very faint 0.5px silver outline.
- Imagery is the focus; typography is placed with generous padding (min 24px) below the image.

### Input Fields
- Minimalist design. Only a bottom border (1px silver) that thickens or darkens slightly on focus. 
- Floating labels using the `label-sm` typography style.

### Navigation
- Top-tier navigation uses high letter-spacing and `label-sm` styling. 
- The active state is indicated by a delicate 1px silver underline or a soft "silver dot" below the item.

### Chips & Tags
- Used for "Artisan Made" or "925 Silver" badges. 
- Transparent backgrounds with a 1px soft-beige border. Typography is extremely light and small.