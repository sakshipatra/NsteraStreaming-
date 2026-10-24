---
name: Cinematic Streaming Experience
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e9bcb6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#af8782'
  outline-variant: '#5e3f3b'
  surface-tint: '#ffb4aa'
  primary: '#ffb4aa'
  on-primary: '#690003'
  primary-container: '#e50914'
  on-primary-container: '#fff7f6'
  inverse-primary: '#c0000c'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#a7c8ff'
  on-tertiary: '#003061'
  tertiary-container: '#0072d7'
  on-tertiary-container: '#f8f9ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930007'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d5e3ff'
  tertiary-fixed-dim: '#a7c8ff'
  on-tertiary-fixed: '#001b3c'
  on-tertiary-fixed-variant: '#004689'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Bebas Neue
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 92px
    letterSpacing: 0.02em
  display-hero-mobile:
    fontFamily: Bebas Neue
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 54px
    letterSpacing: 0.02em
  headline-xl:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.03em
  headline-xl-mobile:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0.03em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0.04em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2.5rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system delivers an immersive, theater-grade digital entertainment environment. Built around an uncompromising dark canvas, it minimizes visual clutter to allow rich video art, cinematic photography, and key artwork to command user focus. 

The aesthetic is High-Contrast Cinematic Minimalist:
- **Atmosphere:** Deep obsidian backdrops evoke the dimmed lights of a cinema, shifting the mental model from browsing software to consuming prestige entertainment.
- **Accent Rhythm:** Strategic strikes of vivid crimson red focus attention exclusively on critical interactions: active tabs, brand signatures, and high-conversion calls-to-action.
- **Tone:** Premium, commanding, effortless, and entertainment-first. Interfaces prioritize visual richness over dense textual utility.

## Colors
The palette balances light absorption with surgical strikes of high-visibility accents:

- **Primary (`#E50914`):** The signature crimson red. Used strictly for prime actions (Primary CTA buttons, active playback scrubbers, selected navigation markers, and featured content highlights). Its darker sibling (`#B81D24`) provides hover/active state grounding.
- **Secondary (`#FFFFFF`):** Pure white used for high-impact display titles, hero typography, and the iconic high-contrast circular play buttons.
- **Surfaces & Backgrounds:**
  - `Canvas Base`: `#0B0B0B` for ultra-deep pitch black environments (video player chrome, hero gradient underlays).
  - `Surface Default`: `#141414` for standard viewports and base containers.
  - `Surface Elevated`: `#1F1F1F` for resting cards, search trays, and secondary overlays.
  - `Surface Highlight`: `#2A2A2A` for card hover states, active borders, and subtle dividers.
- **Neutral Typography & Metadata:**
  - `Text Primary`: `#FFFFFF` for titles, card names, and primary actions.
  - `Text Secondary`: `#A3A3A3` for episode numbers, release years, audio specs, and ratings.
  - `Text Muted`: `#737373` for tertiary legal text, breadcrumbs, and disabled states.

## Typography
The typographic architecture pairs the monumental, cinematic drama of **Bebas Neue** with the neutral precision of **Inter**.

- **Display & Headline Levels (`Bebas Neue`):** All headline levels use all-caps styling. The condensed, statuesque profile emulates cinematic posters and billboards. Letter spacing is slightly expanded (`0.02em` to `0.04em`) to ensure instant legibility across ambient-lit living rooms and bright mobile viewports.
- **Body & Metadata Levels (`Inter`):** Selected for high micro-legibility against dark backdrops. Medium and semi-bold weights handle dense entertainment metadata (e.g., `4K Ultra HD`, `HDR`, `Dolby Atmos`, maturity ratings) without visual vibrating or halation effects.

## Layout & Spacing
The layout follows a continuous horizontal-lane architecture layered onto a fluid multi-column grid.

- **Grid Architecture:** 
  - Mobile (< 768px): 4-column layout, 1rem margin, 1rem gutter.
  - Tablet (768px - 1024px): 8-column layout, 2.5rem margin, 1rem gutter.
  - Desktop (> 1024px): 12-column layout, 4rem margin, 1.5rem gutter. Max-width container capped at 1920px with centered margin overhang.
- **Horizontal Content Rows (Shelves):** Poster collections bleed past right margin edges to signal horizontal scrollability. Row-to-row spacing is generous (`space-xl`), ensuring titles and metadata are distinct from adjacent vertical categories.
- **Hero Billboard Space:** Top billboard components span edge-to-edge horizontally and utilize dynamic viewport height (75vh to 85vh on desktop; 65vh on mobile) with soft gradient transitions into subsequent horizontal shelves.

## Elevation & Depth
Depth is constructed through atmospheric layering and tonal stacking rather than stark drop shadows:

1. **Base Layer (Elevation 0):** Pure canvas `#0B0B0B` to `#141414`.
2. **Surface Layer (Elevation 1):** Resting thumbnail tiles, rows, and navbars (`#1F1F1F`) blending over the canvas via solid surface color without borders.
3. **Hover & Focus Layer (Elevation 2):** Expanded preview cards and drop-down menus scale up (1.05x to 1.15x) using a subtle outer ambient glow: `0px 12px 32px rgba(0, 0, 0, 0.85)` coupled with a low-contrast border `1px solid rgba(255, 255, 255, 0.15)`.
4. **Cinematic Overlays & Scrims:** 
   - Gradients always use directional transparency ramps (`linear-gradient(to top, #141414 0%, transparent 60%)`) to guarantee metadata contrast over vibrant key art.
   - Modal backdrops utilize backdrop blur (`backdrop-filter: blur(20px)`) over an `80%` opacity `#000000` surface.

## Shapes
The design system employs a disciplined, soft geometry (`roundedness: 1`):
- **Standard Corners (0.25rem / 4px):** Applied to thumbnail cards, primary action buttons, form inputs, video player controls, and progress tracks. This subtle curve softens hard digital edges while maintaining an architectural, cinematic structure.
- **Badges & Overlays (0.125rem / 2px to 0.25rem / 4px):** Age rating tags (e.g., `TV-MA`, `PG-13`), resolution indicators (`4K`, `HD`), and audio tags are sharp, compact rectilinear blocks.
- **Circular Elements:** Reserved strictly for round playback controls (Play, Pause, Mute, Add to List circular buttons), creating immediate affordance contrast against rectangular media cards.

## Components

### Buttons
- **Primary Play Button:** Solid white background (`#FFFFFF`), pure black text (`#000000`), bold weight. Soft 4px radius. High-contrast hover state switches to `rgba(255, 255, 255, 0.75)`. Minimum height of 48px for desktop, 44px on touch screens.
- **Secondary Action Button:** Semitransparent surface (`rgba(109, 109, 110, 0.7)`), crisp white text (`#FFFFFF`), with icon prefix. Hover transition shifts surface to `rgba(109, 109, 110, 0.4)`.
- **Destructive / Accent Button:** Crimson red (`#E50914`), white text. Active and hover states transition to `#B81D24`.

### Movie & Series Cards
- **Structure:** 16:9 widescreen or 2:3 key art vertical ratios. Surfaces sit at `#1F1F1F`.
- **Badges:** Placed in top-left or top-right corners with an offset of 8px. Background: `#E50914` for "Top 10" or "New Episode" tags; `rgba(0, 0, 0, 0.65)` with a 1px border `rgba(255, 255, 255, 0.2)` for metadata (`HDR`, `Ultra 4K`).
- **Progress Bars:** Positioned flush along the bottom card edge. Incomplete track: `rgba(255, 255, 255, 0.3)` at 3px height. Active progress: `#E50914` at full opacity. Expands to 4px on hover.

### Chips & Filters
- Compact 32px height chips with a 4px corner radius. Inactive state: `#2A2A2A` background with `#A3A3A3` text. Active state: `#FFFFFF` background with `#000000` text for maximum contrast against the dark background.

### Input Fields & Search
- Inputs use `#141414` background with a 1px border of `rgba(255, 255, 255, 0.3)`. Text color is `#FFFFFF`. On active focus, the border transitions to `#FFFFFF` with no glow ring. Iconography sits in `#A3A3A3`.

### Selection Controls (Checkboxes & Radios)
- Box dimension of 20x20px with a 4px corner for checkboxes and circular geometry for radios. Unchecked: 2px border in `#737373`. Checked: `#E50914` fill with pure white tick icon or center indicator dot.

### Video Player Scrub Bar & Controls
- Scrubber track height 4px, transitioning to 8px on user touch/hover. Unbuffered track: `rgba(255, 255, 255, 0.2)`. Buffer fill: `rgba(255, 255, 255, 0.4)`. Playhead progress: `#E50914`. Playhead thumb: Circular 16px white dot visible on interaction.