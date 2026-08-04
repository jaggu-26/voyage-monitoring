# GeoServe Design Foundation
> Single source of truth for tokens, values, and usage rules across the Pelagos Design System.
> Claude must read this file before generating any UI, component, page, or layout for GeoServe.

---

## 1. Colour Palette

### Brand Primary

| Token | Value | Usage |
|---|---|---|
| `--prim-marine` | `#1852FE` | Primary brand colour — CTAs, links, active states |
| `--color-brand` | `var(--prim-marine)` | Semantic alias — always use this over the primitive |
| `--color-brand-hover` | `#1242d4` | Hover state on brand elements |
| `--color-brand-active` | `#0d3299` | Pressed/active state |
| `--color-brand-subtle` | `var(--prim-blue-10)` = `#eef6ff` | Subtle tinted backgrounds |
| `--color-brand-border` | `var(--prim-blue-100)` = `#bedbfe` | Tinted borders |

### Blue Scale (Primitive)

| Token | Value |
|---|---|
| `--prim-blue-900` | `#001e4c` |
| `--prim-blue-800` | `#1f3a8a` |
| `--prim-blue-700` | `#1d40af` |
| `--prim-blue-600` | `#1c4ed8` |
| `--prim-blue-500` | `#2463eb` |
| `--prim-blue-400` | `#3b81f6` |
| `--prim-blue-300` | `#5fa5f9` |
| `--prim-blue-200` | `#92c5fd` |
| `--prim-blue-100` | `#bedbfe` |
| `--prim-blue-50`  | `#dbeafe` |
| `--prim-blue-10`  | `#eef6ff` |

### Grey / Neutral Scale

| Token | Value | Role |
|---|---|---|
| `--prim-grey-900` | `#030712` | Darkest — page background overlay |
| `--prim-grey-800` | `#10172a` | Sidebar, nav background |
| `--prim-grey-700` | `#1e293b` | Default body text |
| `--prim-grey-600` | `#334154` | Secondary text |
| `--prim-grey-500` | `#475569` | Tertiary text, icons |
| `--prim-grey-400` | `#64748b` | Placeholder, muted labels |
| `--prim-grey-300` | `#94a3b8` | Disabled text |
| `--prim-grey-200` | `#cbd5e1` | Strong borders |
| `--prim-grey-100` | `#e2e8f0` | Default borders |
| `--prim-grey-50`  | `#f1f5f9` | Subtle surface / hover |
| `--prim-grey-10`  | `#f7fafc` | Page background |
| `--prim-white`    | `#ffffff` | Surface default |
| `--prim-black`    | `#000000` | Pure black |

### Status Colours

#### Red / Danger
| Token | Value |
|---|---|
| `--prim-red-900` | `#450a0b` |
| `--prim-red-800` | `#7f1c1d` |
| `--prim-red-700` | `#981b1b` |
| `--prim-red-600` | `#b91c1b` |
| `--prim-red-500` | `#dc2625` |
| `--prim-red-400` | `#ef4444` |
| `--prim-red-300` | `#f77171` |
| `--prim-red-200` | `#fca5a5` |
| `--prim-red-100` | `#fecaca` |
| `--prim-red-50`  | `#fde2e2` |
| `--prim-red-10`  | `#fef1f2` |

#### Yellow / Warning
| Token | Value |
|---|---|
| `--prim-yellow-900` | `#412007` |
| `--prim-yellow-800` | `#713e11` |
| `--prim-yellow-700` | `#844d0f` |
| `--prim-yellow-600` | `#a16207` |
| `--prim-yellow-500` | `#ca8a03` |
| `--prim-yellow-400` | `#eab305` |
| `--prim-yellow-300` | `#facc14` |
| `--prim-yellow-200` | `#fde046` |
| `--prim-yellow-100` | `#feef89` |
| `--prim-yellow-50`  | `#fef9c3` |
| `--prim-yellow-10`  | `#fefce8` |

#### Orange
| Token | Value |
|---|---|
| `--prim-orange-900` | `#5c2a06` |
| `--prim-orange-800` | `#a34706` |
| `--prim-orange-700` | `#c25203` |
| `--prim-orange-600` | `#ce5b0a` |
| `--prim-orange-500` | `#e76a10` |
| `--prim-orange-400` | `#fb7d24` |
| `--prim-orange-300` | `#ff9348` |
| `--prim-orange-200` | `#ffa96b` |
| `--prim-orange-100` | `#ffb988` |
| `--prim-orange-50`  | `#ffe0ca` |
| `--prim-orange-10`  | `#fff3eb` |

#### Green / Success
| Token | Value |
|---|---|
| `--prim-green-900` | `#0a3b1c` |
| `--prim-green-800` | `#0e4f26` |
| `--prim-green-700` | `#147638` |
| `--prim-green-600` | `#1b9e4b` |
| `--prim-green-500` | `#22c55e` |
| `--prim-green-400` | `#4ed17e` |
| `--prim-green-300` | `#7adc9e` |
| `--prim-green-200` | `#a7e8bf` |
| `--prim-green-100` | `#bdeecf` |
| `--prim-green-50`  | `#d3f3df` |
| `--prim-green-10`  | `#e9f9ef` |

#### Teal / Accent
| Token | Value |
|---|---|
| `--prim-teal-900` | `#01443c` |
| `--prim-teal-800` | `#006559` |
| `--prim-teal-700` | `#008475` |
| `--prim-teal-600` | `#00aa97` |
| `--prim-teal-500` | `#00dac1` |
| `--prim-teal-400` | `#00f0d4` |
| `--prim-teal-300` | `#42f8e3` |
| `--prim-teal-200` | `#7cf7e8` |
| `--prim-teal-100` | `#99fbef` |
| `--prim-teal-50`  | `#b9fff7` |
| `--prim-teal-10`  | `#e6fefb` |

### Semantic Colour Tokens

Use these in components — never use raw hex values directly.

#### Danger
| Token | Maps to |
|---|---|
| `--color-danger`        | `--prim-red-500` = `#dc2625` |
| `--color-danger-hover`  | `--prim-red-600` = `#b91c1b` |
| `--color-danger-active` | `--prim-red-700` = `#981b1b` |
| `--color-danger-subtle` | `--prim-red-10`  = `#fef1f2` |
| `--color-danger-border` | `--prim-red-100` = `#fecaca` |

#### Text
| Token | Maps to |
|---|---|
| `--color-text-default`     | `--prim-grey-900` = `#030712` |
| `--color-text-secondary`   | `--prim-grey-600` = `#334154` |
| `--color-text-placeholder` | `--prim-grey-400` = `#64748b` |
| `--color-text-disabled`    | `--prim-grey-300` = `#94a3b8` |
| `--color-text-inverse`     | `--prim-white`    = `#ffffff` |
| `--color-text-brand`       | `--color-brand`   = `#1852FE` |
| `--color-text-danger`      | `--color-danger`  = `#dc2625` |

#### Surface
| Token | Maps to |
|---|---|
| `--color-surface-default` | `--prim-white`    = `#ffffff` |
| `--color-surface-subtle`  | `--prim-grey-10`  = `#f7fafc` |
| `--color-surface-overlay` | `--prim-grey-50`  = `#f1f5f9` |

#### Border
| Token | Maps to |
|---|---|
| `--color-border-default` | `--prim-grey-100` = `#e2e8f0` |
| `--color-border-subtle`  | `--prim-grey-50`  = `#f1f5f9` |
| `--color-border-strong`  | `--prim-grey-200` = `#cbd5e1` |

### Status Chip Colour Mapping (`.gs-cs`)

| Variant | Background | Text |
|---|---|---|
| grey   | `--prim-grey-100` | `--prim-grey-700` |
| blue   | `--prim-blue-50`  | `--prim-blue-700` |
| red    | `--prim-red-100`  | `--prim-red-600`  |
| yellow | `--prim-yellow-100` | `--prim-yellow-800` |
| orange | `--prim-orange-100` | `--prim-orange-900` |
| teal   | `--prim-teal-100`   | `--prim-teal-900`   |
| green  | `--prim-green-100`  | `--prim-green-800`  |

---

## 2. Typography

### Font Families

| Token | Value | Usage |
|---|---|---|
| `--prim-font-primary` | `'Gilroy', -apple-system, BlinkMacSystemFont, sans-serif` | All UI text |
| `--prim-font-mono`    | `'SF Mono', 'Fira Code', monospace` | Code blocks, technical strings |

> **Aliases:** `--font-sans` = `--prim-font-primary`, `--font-mono` = `--prim-font-mono`

Gilroy must be loaded via `Assets/gilroy.zip`. It is the sole display and body font — never use system fonts directly in GeoServe UI.

### Font Sizes

| Token | Value | Usage |
|---|---|---|
| `--prim-font-size-2xs` | `10px` | Micro captions (cascade sub-labels, tag counts) |
| `--prim-font-size-xs`  | `11px` | Labels, badges, legal |
| `--prim-font-size-sm`  | `12px` | Captions, helper text, section labels |
| `--prim-font-size-md`  | `14px` | **Default body text** |
| `--prim-font-size-lg`  | `16px` | Subheadings, input values |
| `--prim-font-size-xl`  | `18px` | Card/section titles (Title 2) |
| `--prim-font-size-2xl` | `20px` | Section headings |
| `--prim-font-size-3xl` | `24px` | Page headings |
| `--prim-font-size-4xl` | `32px` | Hero / display headings |

### Font Weights

| Token | Value | Usage |
|---|---|---|
| `--prim-font-weight-regular`   | `400` | Body text |
| `--prim-font-weight-medium`    | `500` | Emphasis, table cells, secondary captions |
| `--prim-font-weight-semibold`  | `600` | Labels, nav items, button text, card titles |
| `--prim-font-weight-bold`      | `700` | Headings |
| `--prim-font-weight-extrabold` | `800` | Display / hero text |

### Line Heights

| Token | Value | Usage |
|---|---|---|
| `--prim-line-height-tight`   | `1.25` | Headings, compact labels |
| `--prim-line-height-normal`  | `1.5`  | **Default body text** |
| `--prim-line-height-relaxed` | `1.65` | Long-form prose |

### Named Type Styles (Gilroy) — source of truth from Figma

These are the actual named text styles used across Figma components. **Always match a component's text to one of these rows exactly** — size, weight, and line-height travel together as a single style, never mixed and matched.

| Style name | Size | Weight | Line-height | Usage |
|---|---|---|---|---|
| Title 1 B       | `24px` | Bold (`700`)     | `32px` | Page headings |
| Title 2 SB      | `18px` | SemiBold (`600`) | `24px` | Card / section titles (e.g. "Guide Lookup & Procedures") |
| Subtitle 2 B    | `16px` | Bold (`700`)     | `24px` | Modal titles |
| Subtitle 2 SB   | `16px` | SemiBold (`600`) | `24px` | Subheadings |
| Body SB         | `14px` | SemiBold (`600`) | `20px` | Emphasis body text, button labels, guide names |
| Body M          | `14px` | Medium (`500`)   | `20px` | Dropdown list items, secondary emphasis |
| Body R          | `14px` | Regular (`400`)  | `20px` | Default body copy, procedure/category text |
| Caption 1 SB    | `12px` | SemiBold (`600`) | `16px` | Section labels, badges, numbered-step chips |
| Caption 1 M     | `12px` | Medium (`500`)   | `16px` | Secondary captions (e.g. "Automatically selected...") |
| Caption 2 SB    | `10px` | SemiBold (`600`) | `16px` | Micro sub-labels (cascade "Match found"/"Skipped") |

### Typography Scale — Practical Combinations

| Role | Size | Weight | Line-height |
|---|---|---|---|
| Display heading | `32px` | `800` | `1.25` |
| Page heading    | `24px` | `700` | `1.25` |
| Section heading | `20px` | `700` | `1.25` |
| Card title      | `18px` | `600` | `24px` (Title 2 SB) |
| Subheading      | `16px` | `600` | `1.5`  |
| Body default    | `14px` | `400` | `1.5`  |
| Body emphasis   | `14px` | `600` | `1.5`  |
| Body medium     | `14px` | `500` | `1.5`  |
| Caption         | `12px` | `400` | `1.5`  |
| Caption medium  | `12px` | `500` | `16px` |
| Caption emphasis| `12px` | `600` | `16px` |
| Micro caption   | `10px` | `600` | `16px` |
| Label/Badge     | `11px` | `600` | `1.25` |

---

## 3. Spacing

Spacing uses a base-4 scale. Always use tokens — never hardcode px values in components.

### Primitive Spacing Tokens

| Token | Value |
|---|---|
| `--prim-space-1`  | `4px`  |
| `--prim-space-2`  | `8px`  |
| `--prim-space-3`  | `12px` |
| `--prim-space-4`  | `16px` |
| `--prim-space-5`  | `20px` |
| `--prim-space-6`  | `24px` |
| `--prim-space-8`  | `32px` |
| `--prim-space-10` | `40px` |
| `--prim-space-12` | `48px` |
| `--prim-space-16` | `64px` |

### Semantic Spacing Aliases

| Token | Resolves to | Value | Usage |
|---|---|---|---|
| `--space-xs`  | `--prim-space-1`  | `4px`  | Icon gaps, tight inline spacing |
| `--space-sm`  | `--prim-space-2`  | `8px`  | Compact element gaps |
| `--space-md`  | `--prim-space-4`  | `16px` | **Default spacing unit** |
| `--space-lg`  | `--prim-space-6`  | `24px` | Section internal gaps |
| `--space-xl`  | `--prim-space-8`  | `32px` | Between sections |
| `--space-2xl` | `--prim-space-10` | `40px` | Large section gaps |
| `--space-3xl` | `--prim-space-12` | `48px` | Page-level separation |

### Spacing Usage Rules

- **Between inline elements:** `4px` (`--space-xs`)
- **Between form fields / list items:** `8px` (`--space-sm`)
- **Component internal padding:** `16px` (`--space-md`)
- **Card/panel internal padding:** `24px` (`--space-lg`)
- **Between page sections:** `32px–40px` (`--space-xl` / `--space-2xl`)
- **Page top/bottom margin:** `48px` (`--space-3xl`)

---

## 4. Padding

Padding follows the same token scale as spacing. Component-specific padding rules:

### Buttons

| Size | Padding (horizontal) | Height |
|---|---|---|
| Large  | `var(--prim-space-6)` = `24px` | `48px` |
| Medium | `var(--prim-space-4)` = `16px` | `40px` |
| Small  | `var(--prim-space-3)` = `12px` | `32px` |

Token references:
```css
--btn-padding-lg: 0 var(--prim-space-6);
--btn-padding-md: 0 var(--prim-space-4);
--btn-padding-sm: 0 var(--prim-space-3);
--btn-height-lg:  48px;
--btn-height-md:  40px;
--btn-height-sm:  32px;
```

### Text Fields (Inputs)

| Size | Height |
|---|---|
| Large  | `40px` |
| Small  | `32px` |

Internal horizontal padding: `var(--space-md)` = `16px`

### Cards / Panels

| Context | Padding |
|---|---|
| Default card      | `24px` (`--space-lg`) |
| Compact card      | `16px` (`--space-md`) |
| Section container | `24px–32px` |
| Page content area | `48px` top/bottom, `32px` sides |

### Table Cells

| Context | Padding |
|---|---|
| Header cell | `8px 16px` |
| Body cell   | `10px 16px` |
| Checkbox cell | `0` (fixed `44px` width, centered) |

---

## 5. Shadows

### Primitive Shadow Tokens

| Token | Value | Usage |
|---|---|---|
| `--prim-shadow-none` | `none`                              | No elevation |
| `--prim-shadow-xs`   | `0 1px 2px rgba(0,0,0,0.05)`        | Subtle lift |
| `--prim-shadow-sm`   | `0 1px 3px rgba(0,0,0,0.08)`        | Cards, inputs |
| `--prim-shadow-md`   | `0 4px 16px rgba(0,0,0,0.10)`       | Dropdowns, popovers |
| `--prim-shadow-lg`   | `0 8px 32px rgba(0,0,0,0.14)`       | Modals, sidesheets |
| `--prim-shadow-xl`   | `0 20px 60px rgba(0,0,0,0.18)`      | Full-screen overlays |

### Semantic Shadow Aliases

| Token | Resolves to | Context |
|---|---|---|
| `--shadow-xs`       | `--prim-shadow-xs` | Floating labels, badges |
| `--shadow-sm`       | `--prim-shadow-sm` | Default card elevation |
| `--shadow-md`       | `--prim-shadow-md` | Hover card elevation |
| `--shadow-lg`       | `--prim-shadow-lg` | Modals |
| `--shadow-card`     | `--prim-shadow-sm` | All `.card` components |
| `--shadow-dropdown` | `--prim-shadow-md` | All dropdown/select menus |
| `--shadow-modal`    | `--prim-shadow-lg` | Modal dialogs, drawers |

### Shadow Usage Rules

- Default resting state: `--shadow-card` (`shadow-sm`)
- On hover: elevate one step → `--shadow-md`
- Never apply shadow to inline/text elements
- Dark backgrounds: do not use shadow — use border or opacity instead

---

## 6. Border Radius

### Primitive Radius Tokens

| Token | Value | Usage |
|---|---|---|
| `--prim-radius-none` | `0`      | No rounding — tables, flush layouts |
| `--prim-radius-xs`   | `2px`    | Tooltips, micro elements |
| `--prim-radius-sm`   | `4px`    | **Default** — buttons, inputs, chips, badges |
| `--prim-radius-md`   | `8px`    | Cards, dropdowns, modals |
| `--prim-radius-lg`   | `12px`   | Large cards, panels, drawers |
| `--prim-radius-xl`   | `16px`   | Feature cards, hero sections |
| `--prim-radius-2xl`  | `24px`   | Prominent display cards |
| `--prim-radius-full` | `9999px` | Pills, avatars, toggle tracks |

### Semantic Radius Aliases

| Token | Resolves to | Applied to |
|---|---|---|
| `--radius-sm`   | `--prim-radius-sm` = `4px`    | Buttons, inputs, chips, code blocks |
| `--radius-md`   | `--prim-radius-md` = `8px`    | Cards, popovers, dropdowns |
| `--radius-lg`   | `--prim-radius-lg` = `12px`   | Modals, large panels |
| `--radius-xl`   | `--prim-radius-xl` = `16px`   | Feature highlights |
| `--radius-full` | `--prim-radius-full` = `9999px` | Pills, avatars, toggles |

### Radius Usage Rules

- Buttons → always `--radius-sm` (`4px`)
- Form inputs → always `--radius-sm` (`4px`)
- Status chips → always `--radius-sm` (`4px`)
- Component cards / containers → `--radius-md` or `--radius-lg`
- Avatars, icon circles, tags → `--radius-full`
- Tables → `0` on cells, `--radius-md` on the outer wrapper

---

## 7. Icons & Illustrations

### Icon System

GeoServe uses **Lucide Icons** as the primary icon set. Icons should:
- Match the surrounding text size (default `16px`, large `20px`, small `14px`)
- Use `currentColor` for fill/stroke so they inherit text colour
- Use `stroke-width: 1.5` for standard icons, `1.75` for small icons below 14px
- Never be scaled with CSS `transform` — set `width`/`height` directly

**Icon sizes:**

| Context | Size |
|---|---|
| Inline with body text | `14px` |
| Button icon           | `16px` |
| Tab / nav icon        | `18px` |
| Section heading icon  | `20px` |
| Empty state           | `48px` |

**Icon colour:** always use a semantic text token or `currentColor` — never hardcode hex on icons.

### Icon Storage

Local icon files (SVG) live in:
```
assets/Icons/
```
Place new SVG icons here. Name files with kebab-case matching the Lucide icon name, e.g. `arrow-right.svg`, `check-circle.svg`. (Existing files `document-filled.svg` and `Check-Circle.svg` predate this rule — match new additions to kebab-case going forward rather than renaming and risking broken references.)

### Illustration System

Illustrations live in:
```
Assets/illustrations/
```

Current illustrations follow the naming convention `img-{context}.svg`, e.g.:
- `img-empty-no-search.svg` — empty state: no search results
- `img-empty-nothing-here.svg` — empty state: no data
- `img-empty-deleted.svg` — empty state: deleted items
- `img-calendar.svg` — contextual: scheduling
- `img-assign-user.svg` — contextual: user assignment

**Illustration usage rules:**
- Use only for empty states, onboarding, and feature introductions
- Max width: `160px` for inline empty states, `240px` for full-page empty states
- Do not tint or recolour SVG illustrations — use as-is
- Always pair with a heading and a short action prompt

---

## Token Hierarchy Summary

```
Tier 1 — Primitive  →  raw values  (--prim-*)
Tier 2 — Semantic   →  role-based aliases  (--color-brand, --shadow-card, etc.)
Tier 3 — Component  →  component-specific tokens  (--btn-*, --tf-*, etc.)
```

**Rule:** Always use the highest tier available. Prefer `--color-brand` over `--prim-marine`. Prefer `--btn-height-md` over a hardcoded `40px`. Fall back to semantic tokens if no component token exists. Never use raw hex values in component CSS unless defining a primitive token.

---

## Quick Reference — Most Used Tokens

```css
/* Brand */
--color-brand:          #1852FE
--color-brand-hover:    #1242d4

/* Text */
--color-text-default:   #030712
--color-text-secondary: #334154
--color-text-disabled:  #94a3b8

/* Surface */
--color-surface-default: #ffffff
--color-surface-subtle:  #f7fafc

/* Border */
--color-border-default:  #e2e8f0

/* Spacing */
--space-xs: 4px  |  --space-sm: 8px  |  --space-md: 16px
--space-lg: 24px |  --space-xl: 32px |  --space-2xl: 40px

/* Radius */
--radius-sm: 4px  |  --radius-md: 8px
--radius-lg: 12px |  --radius-full: 9999px

/* Shadow */
--shadow-card:     0 1px 3px rgba(0,0,0,0.08)
--shadow-dropdown: 0 4px 16px rgba(0,0,0,0.10)
--shadow-modal:    0 8px 32px rgba(0,0,0,0.14)

/* Typography */
--prim-font-primary: 'Gilroy', sans-serif
--prim-font-size-md: 14px  (body default)
--prim-font-size-lg: 16px  (subheadings)
--prim-font-weight-semibold: 600  (UI labels)
--prim-font-weight-bold:     700  (headings)
```
