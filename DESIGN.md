---
name: Sugarplum Portfolio
colors:
  surface: '#fcf8fd'
  surface-dim: '#dcd9de'
  surface-bright: '#fcf8fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f2f7'
  surface-container: '#f0edf2'
  surface-container-high: '#ebe7ec'
  surface-container-highest: '#e5e1e6'
  on-surface: '#1c1b1f'
  on-surface-variant: '#554247'
  inverse-surface: '#313034'
  inverse-on-surface: '#f3eff4'
  outline: '#887177'
  outline-variant: '#dbc0c6'
  surface-tint: '#a23760'
  primary: '#a23760'
  on-primary: '#ffffff'
  primary-container: '#ec729c'
  on-primary-container: '#670333'
  inverse-primary: '#ffb1c7'
  secondary: '#6150ac'
  on-secondary: '#ffffff'
  secondary-container: '#af9eff'
  on-secondary-container: '#412f8a'
  tertiary: '#006b5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#36ab95'
  on-tertiary-container: '#003930'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e2'
  primary-fixed-dim: '#ffb1c7'
  on-primary-fixed: '#3e001d'
  on-primary-fixed-variant: '#831e48'
  secondary-fixed: '#e6deff'
  secondary-fixed-dim: '#cabeff'
  on-secondary-fixed: '#1c0062'
  on-secondary-fixed-variant: '#493792'
  tertiary-fixed: '#88f6dd'
  tertiary-fixed-dim: '#6bd9c1'
  on-tertiary-fixed: '#00201a'
  on-tertiary-fixed-variant: '#005144'
  background: '#fcf8fd'
  on-background: '#1c1b1f'
  surface-variant: '#e5e1e6'
typography:
  display-lg:
    fontFamily: Epilogue
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Epilogue
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 46px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system crafts an affectionate, creative, and distinctively confectionery portfolio experience tailored for students and emerging creatives. Drawing from playful modernism, it balances whimsical confectionery hues with editorial restraint. 

The aesthetic is approachable, tactile, and bright without veering into juvenile territory. Frosted surfaces evoke marshmallow fluff and spun sugar, while crisp dark berry typography guarantees rigorous legibility and academic-to-professional credibility. Interfaces should evoke warmth, optimism, craftsmanship, and delight.

## Colors

The palette mimics a curated confectionery showcase grounded by rich berry pigments.

- **Primary (`#ec729c` - Bubblegum Rose):** Used for focal interactive actions, featured work tags, and primary CTAs.
- **Secondary (`#9c8beb` - Candied Lavender):** Applied to supporting badges, secondary actions, and subtle structural gradients.
- **Tertiary (`#6edcc4` - Sweet Mint):** Reserved for success states, interactive tags, and refreshing accent moments.
- **Quaternary Accents:** Soft peach (`#ffb997`) and baby blue (`#98d9f7`) serve as auxiliary tags for creative project disciplines (e.g., UX, Illustration, Motion).
- **Surfaces (`#fcf8fd` - Marshmallow Cream / Soft Violet White):** Creates a plush, non-sterile canvas with a warm, sugary undertone.
- **Typography & High Contrast Elements:** Deep plum-slate (`#2d2036`) and rich berry (`#3d284a`) are strictly enforced for body copy, headers, and essential borders to exceed WCAG AAA readability against pastel surfaces.

## Typography

The typography couples the expressive, sculptural geometry of Epilogue for headlines with the clean, rounded friendliness of Plus Jakarta Sans for body copy and navigational labels.

Epilogue provides punchy, editorial personality suited for student project titles and introduction callouts. Plus Jakarta Sans preserves clarity and openness across small screens, dense project case studies, and resume specs. High-contrast plum text (`#2d2036`) anchors all scales, ensuring soft pastel backgrounds never impair reading stamina.

## Layout & Spacing

The portfolio structure follows a 12-column responsive fluid grid designed to display visual artifacts with generous breathing room:

- **Desktop (1024px+):** 12 columns, 1.5rem gutters, 3rem margins, capped at a maximum container width of 1240px to retain intimacy.
- **Tablet (768px - 1023px):** 8 columns, 1.25rem gutters, 2rem margins.
- **Mobile (Below 768px):** 4 columns, 1rem gutters, 1.25rem margins.

Vertical rhythm relies on wide spacing tokens (`space-lg`, `space-xl`) between portfolio sections to give case studies gallery-grade separation. Component padding maintains a plump, pillowy footprint with generous top-to-bottom balance.

## Elevation & Depth

Visual hierarchy uses frosted marshmallow layering rather than aggressive dark shadows.

- **Surface Tiers:** Backgrounds sit on `#fcf8fd`. Elevated card containers use pure white `#ffffff` or tinted pastel glazes (e.g., lavender `#f6f3ff` or mint `#f0fbf7`).
- **Shadows:** Depth is conveyed through diffuse, candy-tinted ambient glows. Shadows use 0px to 4px horizontal offset, 8px to 24px blur, and low-opacity plum tint (`rgba(61, 40, 74, 0.06)` to `rgba(61, 40, 74, 0.10)`).
- **Outlines:** All cards and floating surfaces utilize a fine 1px translucent border (`rgba(61, 40, 74, 0.08)` or solid pastel rings) to preserve structure and definition against white media embeds.

## Shapes

The shape vocabulary emphasizes soft curves and organic cushion contours. 

Base components (buttons, input fields, and chips) adopt friendly radii (8px/0.5rem) or full pills. Project presentation cards, modals, and embedded mockups step up to `rounded-lg` (16px/1rem) and `rounded-xl` (24px/1.5rem), creating a smooth, confectionery aesthetic that feels soft to the touch without compromising image frames.

## Components

### Buttons
- **Primary:** Bubblegum rose background (`#ec729c`), white bold label, pill or 12px rounded corner. Hover applies a gentle scale (`scale(1.02)`) and an illuminated soft pink glow (`box-shadow: 0 8px 20px rgba(236, 114, 156, 0.35)`). Active state depresses slightly.
- **Secondary:** Candied lavender tint background (`#f1eeff`) with plum text (`#2d2036`) and a subtle 1px border (`#9c8beb`).
- **Tertiary / Ghost:** Transparent background, deep plum label, pastel hover wash.

### Chips & Badges
- Compact pill-shaped metadata tags representing disciplines (e.g., "UI Design", "3D Modeling", "Case Study").
- Tinted candy fills: Lavender (`#efeaff`), Mint (`#e4f9f3`), Peach (`#ffece3`), or Baby Blue (`#e8f6fd`), paired with high-contrast `#2d2036` text.

### Cards (Project & Experience)
- **Background:** Solid crisp white (`#ffffff`) or 70% opacity frosted glass with backdrop blur.
- **Border:** 1.5px continuous outline in muted berry-tint (`rgba(61, 40, 74, 0.08)`).
- **Hover Behavior:** 4px vertical lift, ambient plum shadow expansion, and optional corner tag animation.
- **Inner Padding:** Generous `space-md` or `space-lg` to create a framed artwork aesthetic.

### Input Fields
- Soft marshmallow white fill (`#ffffff`), 1.5px soft border in `#e9dfed`.
- Focus state reveals a 2px sweet mint (`#6edcc4`) or bubblegum (`#ec729c`) ring with matching subtle glow. Placeholder text styled in muted plum-slate (`#766580`).

### Checkboxes & Radio Buttons
- Rounded squares for checkboxes (6px radius) and full circles for radios.
- Unchecked: `#ffffff` background with 1.5px plum-tint border.
- Checked: Bubblegum rose (`#ec729c`) fill with an optical white checkmark or center pip.

### Lists & Timeline Components
- Used for education milestones, awards, and project indices.
- Alternating subtle candy-tint indicator pips (lavender, mint, bubblegum) connected by a soft 2px plum-neutral hairline rule.

### Media Frames & Lightboxes
- Project thumbnails feature soft interior clipping (`rounded-lg`) accompanied by a subtle inner pastel glow vignette.