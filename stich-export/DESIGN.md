---
name: Elite Security Design System
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1b1b1d'
  surface-container: '#1f1f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e4'
  on-surface-variant: '#c6c6ce'
  inverse-surface: '#e5e2e4'
  inverse-on-surface: '#303032'
  outline: '#909098'
  outline-variant: '#46464d'
  surface-tint: '#bfc5e4'
  primary: '#bfc5e4'
  on-primary: '#292f48'
  primary-container: '#0a1128'
  on-primary-container: '#767c99'
  inverse-primary: '#575d78'
  secondary: '#c6c6c6'
  on-secondary: '#303030'
  secondary-container: '#474747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#e8be9f'
  on-tertiary: '#442b14'
  tertiary-container: '#210d00'
  on-tertiary-container: '#9a765b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#bfc5e4'
  on-primary-fixed: '#141a32'
  on-primary-fixed-variant: '#3f465f'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#e8be9f'
  on-tertiary-fixed: '#2c1603'
  on-tertiary-fixed-variant: '#5e4029'
  background: '#131315'
  on-background: '#e5e2e4'
  surface-variant: '#353436'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Metropolis
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

The design system is built to project absolute authority, discretion, and unwavering protection. It targets a high-net-worth demographic and corporate executives in Colombia, requiring a visual language that balances "Old World" prestige with "Modern Defense" technology.

The style is **Luxury Corporate**, characterized by a dark, immersive color palette, generous whitespace, and high-contrast gold accents. It avoids the "tactical/military" cliché, opting instead for a "concierge-security" aesthetic—refined, polished, and sophisticated. The interface should feel like a premium digital vault: secure, exclusive, and precise.

## Colors

The color palette is anchored in **Deep Midnight Navy** and **Pure Black** to provide a sense of depth and stability. 

- **Primary & Secondary:** Use Deep Midnight Navy (#0A1128) for the main surface containers to distinguish them from the Pure Black (#000000) background, creating a subtle layering effect.
- **Accents:** Metallic Gold (#D4AF37) is reserved for primary actions, critical alerts, and brand signatures. Champagne Gold (#E6BE8A) is used for subtle highlights and secondary interactive states to add warmth.
- **Typography:** Use Crisp White (#FFFFFF) for headings to ensure maximum impact. Silver-Gray (#C0C0C0) is utilized for body text to reduce eye strain and maintain a sophisticated contrast ratio.
- **Overlays:** Use 40% opacity black overlays for modal backdrops to maintain focus on the content.

## Typography

This design system utilizes a high-contrast typographic pairing to evoke both tradition and modernity.

- **Headlines:** Playfair Display provides a serif, "institutional" weight that suggests history and prestige. Display headings should use negative letter-spacing for a tighter, more editorial feel.
- **Body:** Work Sans is chosen for its exceptional legibility on dark backgrounds. It remains clean and neutral, allowing the serif headings to take center stage.
- **Functional Labels:** Metropolis (a modern geometric grotesque) is used for UI labels, buttons, and navigation items to provide a technical, structured contrast to the serif headings.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** grid. On desktop, content is centered within a 1280px container using a 12-column grid. On mobile, a 4-column grid is used with reduced margins.

- **Whitespace:** Emphasize generous vertical spacing (Section Padding) to allow brand imagery and high-end typography to breathe. This "luxury of space" is a core brand pillar.
- **Rhythm:** All spacing must be a multiple of the 8px base unit. 
- **Alignment:** Use a strong vertical axis. Left-align text for readability, but use center-alignment for high-impact hero sections or quote blocks.

## Elevation & Depth

Depth is communicated through **Tonal Layering** rather than heavy drop shadows. This maintains a clean, architectural look.

- **Surface Levels:** The background is Pure Black (#000000). Cards and containers are Deep Midnight Navy (#0A1128). This subtle shift in hue creates a tiered hierarchy.
- **Borders:** Instead of shadows, use "Ghost Outlines"—1px solid borders using the accent gold at very low opacity (10-20%). This defines the edges of elements without cluttering the UI.
- **Active States:** When an element is focused or elevated, increase the border opacity and apply a very soft, diffused glow using the Gold accent color (Blur 20px, Spread 0, Opacity 15%).

## Shapes

The design system employs **Sharp (0px)** corners. This decision reinforces the brand's authoritative, rigid, and disciplined nature. Rectilinear shapes communicate stability and architectural strength.

- **Exceptions:** Very small icons or decorative pill-shaped tags for "Status: Active" may use minimal rounding to differentiate them from structural UI components.
- **Interactive Elements:** Buttons and input fields must maintain 90-degree angles to align with the "secure perimeter" design narrative.

## Components

### Buttons
- **Primary:** Metallic Gold background with black text. Bold, uppercase Metropolis font. High-contrast for clear CTA direction.
- **Secondary:** Transparent background with a 1px Gold border. White text.
- **Tertiary/Ghost:** White text with a Gold underline that appears on hover.

### Cards
- Deep Midnight Navy background with no shadow. 1px Gold-tinted border (#D4AF37 at 15%). 
- Content within cards should have generous padding (min 32px) to maintain the premium feel.

### Input Fields
- Underline style or fully enclosed with a 1px Silver-Gray border.
- Placeholder text in Silver-Gray. On focus, the border transitions to Champagne Gold with a subtle glow.

### Additional Components
- **Status Indicators:** Small, high-saturation LED-style dots (Green for Secure, Red for Alert).
- **Service Accents:** Use thin, vertical Gold lines to separate content sections or as a lead-in to headlines, mimicking a "security detail" or precision line.
- **Data Visualizations:** Minimalist line graphs using Gold and White, set against the Navy background.