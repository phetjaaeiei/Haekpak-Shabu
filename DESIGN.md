---
name: Vibrant Umami
colors:
  surface: '#181212'
  surface-dim: '#181212'
  surface-bright: '#3f3737'
  surface-container-lowest: '#120d0d'
  surface-container-low: '#201a1a'
  surface-container: '#251e1e'
  surface-container-high: '#2f2828'
  surface-container-highest: '#3a3333'
  on-surface: '#ede0df'
  on-surface-variant: '#debfbc'
  inverse-surface: '#ede0df'
  inverse-on-surface: '#362f2f'
  outline: '#a68a88'
  outline-variant: '#57413f'
  surface-tint: '#ffb3ad'
  primary: '#ffb3ad'
  on-primary: '#66050b'
  primary-container: '#801b1b'
  on-primary-container: '#ff8f86'
  inverse-primary: '#a73834'
  secondary: '#ffb68d'
  on-secondary: '#532200'
  secondary-container: '#e66f13'
  on-secondary-container: '#491d00'
  tertiary: '#88db5e'
  on-tertiary: '#113800'
  tertiary-container: '#1a4c00'
  on-tertiary-container: '#70c248'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#86201f'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#ffb68d'
  on-secondary-fixed: '#321200'
  on-secondary-fixed-variant: '#763300'
  tertiary-fixed: '#a3f877'
  tertiary-fixed-dim: '#88db5e'
  on-tertiary-fixed: '#072100'
  on-tertiary-fixed-variant: '#1c5200'
  background: '#181212'
  on-background: '#ede0df'
  surface-variant: '#3a3333'
typography:
  display-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  title-md:
    fontFamily: Be Vietnam Pro
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-bold:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system is built to evoke the sensory excitement of a bustling shabu-shabu restaurant. The brand personality is **energetic, hospitable, and appetizing**. It targets food lovers looking for a premium yet approachable dining experience.

The visual direction is **Modern Corporate with a Tactile Edge**. It combines clean, systematic layouts with high-energy color pops and soft, "pillowy" UI elements that mimic the freshness of ingredients. The goal is to make the digital experience feel as satisfying as the meal itself, using high-contrast typography and rich, warm background tones to create a cozy, "night-out" atmosphere.

## Colors

The palette is derived directly from the fresh ingredients of a hot pot:
- **Primary (Deep Maroon):** Used for primary branding, headers, and core structural elements. It provides a rich, grounded base.
- **Secondary (Bright Orange):** The "heat" color. Used for primary call-to-actions, price tags, and urgent notifications.
- **Tertiary (Fresh Green):** Used to signify health, freshness, and "ready-to-eat" status. Perfect for vegetable categories or dietary labels.
- **Neutral (Dark Umami):** A near-black with red undertones used for backgrounds to make the food photography and vibrant accents pop.
- **Surface Warm:** A lighter chocolate-toned dark for cards and secondary containers to create depth without losing the cozy vibe.

## Typography

We use **Be Vietnam Pro** for its excellent Thai character support and its modern, friendly geometric construction. 

- **Headlines:** Use heavy weights (700-800) to create a bold, "shouting" impact that matches the "Haekpak" (shouting) name.
- **Body:** Stick to regular weights for legibility against dark backgrounds.
- **Price Points:** Use `title-md` or `headline-lg` in the Secondary Orange color to ensure they are the first thing a user sees.
- **Hierarchy:** Maintain clear contrast between product names (Bold) and descriptions (Regular).

## Layout & Spacing

The layout uses a **Fluid Grid** system to accommodate various device sizes, especially mobile for in-restaurant ordering.

- **Mobile:** 4-column grid with 16px margins. Content is mostly single-column stacked cards.
- **Desktop:** 12-column grid with 64px margins. Content uses a mix of spans (e.g., 3-column spans for menu items).
- **Rhythm:** Use an 8px base unit. Component internal padding should be generous (16px-24px) to create a premium, uncrowded feel despite the bold colors.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layering** rather than traditional shadows. 

1. **Background:** Deep Umami (#1A1414).
2. **Surface Level 1:** Surface Warm (#2D1E1E) for large containers and section blocks.
3. **Surface Level 2:** Primary Maroon (#801B1B) for interactive cards or highlighted sections.
4. **Accents:** Secondary Orange for buttons which "float" above the dark background using a soft, orange-tinted ambient glow (e.g., `0px 4px 20px rgba(244, 121, 32, 0.3)`).

## Shapes

The design system uses **Rounded** geometry to feel friendly and organic, like the curves of a shabu pot or fresh ingredients.

- **Standard Elements:** 8px (0.5rem) corner radius for input fields and small cards.
- **Large Containers:** 16px (1rem) for main category cards and modal overlays.
- **Buttons & Chips:** Use fully rounded (pill-shaped) ends to maximize the "friendly" and "modern" aesthetic.

## Components

### Buttons
- **Primary:** Bright Orange background, White text, bold weight. Use for "Add to Cart" or "Book Now."
- **Secondary:** Deep Maroon background with an Orange border.
- **Ghost:** Transparent background with White or Green text for less critical actions like "View Details."

### Food Category Cards
- Use a large background image of the food category (Meats, Veggies, Soups).
- Apply a 40% black gradient overlay from the bottom.
- Place the Category Name (Display-sm) and item count at the bottom left.

### Lists & Menus
- Use Surface Warm containers for menu items.
- Price tags should always be Secondary Orange and positioned at the top right of the item card.
- Green Tertiary color is used for "In Stock" or "Recommended" badges.

### Input Fields
- Dark backgrounds with a subtle Primary Maroon border.
- Focused state uses a 2px Secondary Orange border to guide the user's eye.