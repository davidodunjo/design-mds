---
version: alpha
name: UntitledUI-design-analysis
description: >-
  A neutral-ground application UI system whose entire visual identity rides on a single violet
  brand ramp set against a stock neutral palette. Surfaces are white over neutral-50 in light and
  neutral-950 over neutral-900 in dark; there are no tinted grounds and no second accent hue. Type
  is one humanist sans serving both display and body, running 12px to 72px on a 4px grid, with
  negative tracking applied only from 36px upward and weight confined to 400, 500 and 600 — a
  quiet, functional voice rather than an expressive one. Accent is scarce and structural: brand
  color appears on solid fills, focus rings, progress and selection, and withdraws almost entirely
  from type in dark mode, where every brand text role resolves to neutral. What distinguishes the
  system is its depth grammar — a skeuomorphic inset bevel paired with a masked white inner border
  on every solid control, hairlines drawn as inset rings rather than borders so they never consume
  layout box, and a four-layer token indirection that lets one class name resolve correctly in both
  themes without any per-component dark variant.
colors:
  brand-50: "#F9F5FF"
  brand-100: "#F4EBFF"
  brand-200: "#E9D7FE"
  brand-300: "#D6BBFB"
  brand-400: "#B692F6"
  brand-500: "#9E77ED"
  brand-600: "#7F56D9"
  brand-700: "#6941C6"
  brand-800: "#53389E"
  brand-900: "#42307D"
  brand-950: "#2C1C5F"
  white: "#FFFFFF"
  black: "#000000"
  avatar-neutral: "#E0E0E0"
  app-store-border: "#A6A6A6"
  social-facebook: "#1877F2"
  social-facebook-active: "#0C63D4"
  social-dribbble: "#EA4C89"
  social-dribbble-active: "#E62872"
typography:
  display-2xl:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 72
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -1.44
  display-xl:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 60
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -1.2
  display-lg:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 48
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.96
  display-md:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 36
    fontWeight: 600
    lineHeight: 1.22
    letterSpacing: -0.72
  display-sm:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 30
    fontWeight: 600
    lineHeight: 1.27
    letterSpacing: 0
  display-xs:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 24
    fontWeight: 600
    lineHeight: 1.33
    letterSpacing: 0
  xl-medium:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 20
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0
  lg-regular:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 18
    fontWeight: 400
    lineHeight: 1.56
    letterSpacing: 0
  lg-medium:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 18
    fontWeight: 500
    lineHeight: 1.56
    letterSpacing: 0
  md-regular:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 16
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  md-semibold:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 16
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0
  sm-regular:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 14
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0
  sm-medium:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 14
    fontWeight: 500
    lineHeight: 1.43
    letterSpacing: 0
  sm-semibold:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 14
    fontWeight: 600
    lineHeight: 1.43
    letterSpacing: 0
  xs-regular:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 12
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  xs-medium:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 12
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0
  xs-semibold:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 12
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0
  code-inline:
    fontFamily: 'Inter, -apple-system, "Segoe UI", Roboto, Arial, sans-serif'
    fontSize: 14
    fontWeight: 700
    lineHeight: 1.43
    letterSpacing: 0
rounded:
  none: 0
  xs: 2
  sm: 4
  default: 4
  md: 6
  lg: 8
  xl: 12
  2xl: 16
  3xl: 24
  full: 9999
spacing:
  px: 1
  1: 4
  2: 8
  3: 12
  4: 16
  5: 20
  6: 24
  8: 32
  10: 40
  12: 48
  16: 64
  20: 80
  24: 96
components:
  button-primary:
    backgroundColor: "{colors.brand-600}"
    textColor: "{colors.white}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  button-primary-active:
    backgroundColor: "{colors.brand-700}"
    textColor: "{colors.white}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  button-secondary:
    backgroundColor: "{colors.white}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  button-tertiary:
    backgroundColor: transparent
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  button-link:
    backgroundColor: transparent
    textColor: "{colors.brand-700}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.default}"
    padding: 0
  button-destructive:
    textColor: "{colors.white}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  button-utility:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.lg}"
    padding: 8px
  social-button:
    backgroundColor: "{colors.social-facebook}"
    textColor: "{colors.white}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.lg}"
    padding: 10px 14px
  social-button-active:
    backgroundColor: "{colors.social-facebook-active}"
    textColor: "{colors.white}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.lg}"
    padding: 10px 14px
  app-store-button:
    backgroundColor: "{colors.black}"
    textColor: "{colors.white}"
    rounded: 7px
  input:
    backgroundColor: "{colors.white}"
    typography: "{typography.md-regular}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  textarea:
    backgroundColor: "{colors.white}"
    typography: "{typography.md-regular}"
    rounded: "{rounded.lg}"
    padding: 12px 14px
  label:
    typography: "{typography.sm-medium}"
  hint-text:
    typography: "{typography.sm-regular}"
  checkbox:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.default}"
    size: 16px
  checkbox-active:
    backgroundColor: "{colors.brand-600}"
    textColor: "{colors.white}"
    rounded: "{rounded.default}"
    size: 16px
  radio-button:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 16px
  toggle:
    rounded: "{rounded.full}"
    height: 20px
  toggle-active:
    backgroundColor: "{colors.brand-600}"
    rounded: "{rounded.full}"
    height: 20px
  slider-handle:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 24px
  pin-input:
    typography: "{typography.display-lg}"
    rounded: "{rounded.lg}"
  file-upload:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.xl}"
    padding: 16px 24px
  select-item:
    typography: "{typography.md-regular}"
    padding: 8px 12px
  badge-pill:
    typography: "{typography.sm-medium}"
    rounded: "{rounded.full}"
    padding: 2px 10px
  badge-modern:
    backgroundColor: "{colors.white}"
    typography: "{typography.sm-medium}"
    rounded: "{rounded.md}"
    padding: 2px 10px
  tag:
    typography: "{typography.xs-medium}"
    padding: 3px 8px
  dot-icon:
    rounded: "{rounded.full}"
    size: 10px
  tab:
    typography: "{typography.sm-semibold}"
    padding: 8px 10px
  tab-active:
    backgroundColor: "{colors.brand-50}"
    textColor: "{colors.brand-700}"
    typography: "{typography.sm-semibold}"
    padding: 8px 10px
  table:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.xl}"
  table-header:
    typography: "{typography.xs-semibold}"
    padding: 8px 24px
  table-cell:
    typography: "{typography.sm-regular}"
    padding: 8px 24px
  modal:
    rounded: "{rounded.xl}"
  slideout-menu:
    backgroundColor: "{colors.white}"
  dropdown-popover:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.lg}"
    padding: 4px 6px
  dropdown-item:
    rounded: "{rounded.md}"
    padding: 8px 10px
  tooltip:
    textColor: "{colors.white}"
    typography: "{typography.xs-semibold}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  chart-tooltip:
    textColor: "{colors.white}"
    typography: "{typography.xs-semibold}"
    rounded: "{rounded.lg}"
    padding: 8px 12px
  section-divider:
    height: 1px
  featured-icon-light:
    backgroundColor: "{colors.brand-100}"
    textColor: "{colors.brand-600}"
    rounded: "{rounded.full}"
    size: 40px
  featured-icon-dark:
    backgroundColor: "{colors.brand-600}"
    textColor: "{colors.white}"
    rounded: "{rounded.lg}"
    size: 40px
  featured-icon-modern:
    backgroundColor: "{colors.white}"
    textColor: "{colors.brand-600}"
    rounded: "{rounded.lg}"
    size: 40px
  avatar:
    rounded: "{rounded.full}"
    typography: "{typography.md-semibold}"
    size: 40px
  progress-bar:
    rounded: "{rounded.md}"
    height: 8px
  loading-indicator:
    typography: "{typography.sm-medium}"
    size: 32px
  pagination-item:
    typography: "{typography.sm-medium}"
    rounded: "{rounded.lg}"
    size: 36px
  date-cell:
    rounded: "{rounded.full}"
    typography: "{typography.sm-regular}"
    size: 40px
  date-cell-active:
    backgroundColor: "{colors.brand-600}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    typography: "{typography.sm-medium}"
    size: 40px
  marketing-header:
    backgroundColor: "{colors.white}"
    height: 72px
    padding: 0 16px
  nav-menu-item:
    textColor: "{colors.brand-700}"
    typography: "{typography.md-semibold}"
    rounded: "{rounded.lg}"
    padding: 4px 6px
  nav-item:
    backgroundColor: "{colors.white}"
    typography: "{typography.sm-semibold}"
    rounded: "{rounded.md}"
    height: 36px
    padding: 8px 12px
  sidebar:
    backgroundColor: "{colors.white}"
    padding: 16px
  header-navigation:
    backgroundColor: "{colors.white}"
    height: 64px
---

## Overview

This is a neutral-ground application UI system built on React Aria Components and Tailwind CSS v4. Its entire token layer is expressed as CSS custom properties inside a single Tailwind `@theme` block — the file is `theme.css`, and it is the only place values are declared. There is no JavaScript config object and no design-token JSON; Tailwind generates the utility classes directly from the variable names the theme declares, so adding a token and using it are the same act.

The defining architectural choice is **four-layer token indirection**. A component never names a color; it names a *role*. Roles resolve to ramps, ramps resolve to base palettes, and a parallel set of property-namespaced aliases exists so that one role name emits `bg-*`, `text-*`, `border-*`, `ring-*` and `outline-*` utilities alike:

1. **Base palette** — `--color-brand-50` through `--color-brand-950`, plus a stock `neutral` / `red` / `green` / `yellow` / `blue` set the system inherits and does **not** redefine.
2. **Utility ramps** — `--color-utility-brand-*`, `--color-utility-neutral-*` and twelve more. This is the layer that inverts in dark mode.
3. **Semantic roles** — `--color-text-*`, `--color-bg-*`, `--color-border-*`, `--color-fg-*`, plus a set of roles named for a single consumer.
4. **Property-namespace mirrors** — `--background-color-*`, `--text-color-*`, `--border-color-*`, `--ring-color-*` and `--outline-color-*`, which re-export the same roles so `ring-primary` and `outline-primary` work wherever `bg-primary` does.

Only one palette is authored outright: the brand ramp, a violet scale running `{colors.brand-50}` to `{colors.brand-950}` with `{colors.brand-600}` as the interactive anchor. That anchor is also written into the document's `theme-color` meta tag — the single place the brand color appears outside the token layer, and therefore the one value a re-brand must change by hand.

Dark mode is a **class-scoped variable override**, not a separate theme. A `dark-mode` class on the root element redeclares the roles and flips the utility ramps end-for-end, registered as a custom variant matching `.dark-mode` and its descendants. Because the inversion happens entirely at the ramp and role layers, components carry almost no dark-specific styling.

**Key Characteristics:**

- Role-named color classes only. The system's stated rule is that elements *must* be styled with role classes — `text-primary`, `bg-primary` — and never with raw palette classes such as `text-gray-900` or `bg-blue-700`.
- Single-family typography: `--font-body` and `--font-display` resolve to the same stack. There is no display/body split in the token layer, so hierarchy is carried by size and weight alone.
- The type scale is arithmetic on a single spacing unit rather than literal pixels — each step is declared as a multiple of that unit, which is never overridden, so every size lands on a 4px grid.
- Negative letter-spacing appears only from `{typography.display-md}` upward; everything at 20px and below carries no tracking.
- Elevation is a seven-step neutral shadow ramp plus a **skeuomorphic** pair — an inset hairline over an inset bottom bevel — that marks every solid and outlined control.
- `{rounded.lg}` is the system's default corner, used on more surfaces than any other explicit radius; `{rounded.full}` matches it in reach, carrying all circular and pill geometry.
- Every interactive component is built on React Aria Components, so state styling keys off render-prop booleans — `isSelected`, `isFocusVisible`, `isInvalid` — rather than CSS pseudo-classes alone.
- Disabled state is uniform and token-free: a flat 50% opacity, which deliberately replaced an earlier generation of dedicated disabled color tokens.
- Motion is deliberately minimal — two keyframe animations exist in the whole system, and the house transition is a 100ms linear one.

## Colors

### Brand Ramp

The only palette the system authors. Steps are declared as space-separated `rgb()` triplets; the frontmatter carries their resolved hex equivalents.

| Token | Authored value | Role in the system |
|---|---|---|
| `{colors.brand-50}` | `rgb(249 245 255)` | Backs `bg-brand-primary` and `utility-brand-50` |
| `{colors.brand-100}` | `rgb(244 235 255)` | Backs `bg-brand-secondary` |
| `{colors.brand-200}` | `rgb(233 215 254)` | On-brand secondary and tertiary text; featured-icon light foreground in dark mode |
| `{colors.brand-300}` | `rgb(214 187 251)` | On-brand quaternary text |
| `{colors.brand-400}` | `rgb(182 146 246)` | Dark-mode `border-brand` |
| `{colors.brand-500}` | `rgb(158 119 237)` | `border-brand`, the focus ring, `fg-brand-secondary` |
| `{colors.brand-600}` | `rgb(127 86 217)` | **Interactive anchor** — `bg-brand-solid`, `fg-brand-primary`, the slider handle border, the document theme color |
| `{colors.brand-700}` | `rgb(105 65 198)` | `bg-brand-solid_hover`, `text-brand-secondary` |
| `{colors.brand-800}` | `rgb(83 56 158)` | `bg-brand-section`, `text-brand-secondary_hover` |
| `{colors.brand-900}` | `rgb(66 48 125)` | `text-brand-primary` |
| `{colors.brand-950}` | `rgb(44 28 95)` | Dark-mode `utility-brand-50` |

The system's own re-branding guidance asks for a complete scale from 25 through 950, and names a `--color-brand-25` step as the lightest tint. **That step is not declared and no component references it** — it exists only in the guidance, so a re-brand that supplies it is adding a token rather than replacing one.

### Base Colors

Four values sit above the light-mode block, outside the role system.

- **`transparent`** — `rgb(0 0 0 / 0)`.
- **`{colors.white}`** — fixed; never inverts.
- **`{colors.black}`** — fixed; used directly by the Apple variant of `{component.social-button}` and by `{component.app-store-button}`.
- **`alpha-white` / `alpha-black`** — `{colors.white}` and `{colors.black}` in light mode, **swapped and re-toned** in dark mode to `rgb(12 14 18)` and `rgb(255 255 255)`. The source comments them as values that will invert.

### Background Roles

The `--color-bg-*` family. Light and dark resolutions are given side by side; both are declared explicitly rather than derived.

| Token | Light resolves to | Dark resolves to |
|---|---|---|
| `bg-primary` | `{colors.white}` | `neutral-950` |
| `bg-primary_alt` | `{colors.white}` | `bg-secondary` |
| `bg-primary_hover` | `neutral-50` | `neutral-900` |
| `bg-primary-solid` | `neutral-950` | `bg-secondary` |
| `bg-secondary` | `neutral-50` | `neutral-900` |
| `bg-secondary_alt` | `neutral-50` | `bg-primary` |
| `bg-secondary_hover` | `neutral-100` | `neutral-800` |
| `bg-secondary-solid` | `neutral-600` | `neutral-600` |
| `bg-tertiary` | `neutral-100` | `neutral-800` |
| `bg-quaternary` | `neutral-200` | `neutral-700` |
| `bg-active` | `neutral-50` | `neutral-800` |
| `bg-overlay` | `neutral-950` | `neutral-800` |
| `bg-brand-primary` | `{colors.brand-50}` | `{colors.brand-500}` |
| `bg-brand-primary_alt` | `{colors.brand-50}` | `bg-secondary` |
| `bg-brand-secondary` | `{colors.brand-100}` | `{colors.brand-600}` |
| `bg-brand-solid` | `{colors.brand-600}` | `{colors.brand-600}` |
| `bg-brand-solid_hover` | `{colors.brand-700}` | `{colors.brand-500}` |
| `bg-brand-section` | `{colors.brand-800}` | `bg-secondary` |
| `bg-brand-section_subtle` | `{colors.brand-700}` | `bg-primary` |
| `bg-error-primary` | `red-50` | `red-950` |
| `bg-error-secondary` | `red-100` | `red-600` |
| `bg-error-solid` | `red-600` | `red-600` |
| `bg-error-solid_hover` | `red-700` | `red-500` |
| `bg-warning-primary` | `yellow-50` | `yellow-950` |
| `bg-warning-secondary` | `yellow-100` | `yellow-600` |
| `bg-warning-solid` | `yellow-600` | `yellow-600` |
| `bg-success-primary` | `green-50` | `green-950` |
| `bg-success-secondary` | `green-100` | `green-600` |
| `bg-success-solid` | `green-600` | `green-600` |

Two suffixes carry consistent meaning across the whole family: `_alt` means "collapses onto a different role in dark mode", and `-solid` means "holds its value across both modes". `bg-brand-section` and `bg-brand-section_subtle` are declared in both modes but consumed by nothing — they anticipate brand-colored page bands the component set does not yet build.

### Text Roles

The `--color-text-*` family. Usage descriptions are the system's own.

| Token | Light | Dark | Documented usage |
|---|---|---|---|
| `text-primary` | `neutral-900` | `neutral-50` | Primary text such as page headings |
| `text-secondary` | `neutral-700` | `neutral-300` | Labels and section headings |
| `text-secondary_hover` | `neutral-800` | `neutral-200` | Secondary text, hover state |
| `text-tertiary` | `neutral-600` | `neutral-400` | Supporting and paragraph text |
| `text-tertiary_hover` | `neutral-700` | `neutral-300` | Tertiary text, hover state |
| `text-quaternary` | `neutral-500` | `neutral-400` | Lower-contrast text such as footer column headings |
| `text-placeholder` | `neutral-500` | `neutral-500` | Input placeholders — the system notes `neutral-500` is chosen over `neutral-400` for contrast |
| `text-white` | `{colors.white}` | `{colors.white}` | Always white regardless of mode |
| `text-primary_on-brand` | `{colors.white}` | `neutral-50` | Primary text on solid brand backgrounds |
| `text-secondary_on-brand` | `{colors.brand-200}` | `neutral-300` | Secondary text on solid brand backgrounds |
| `text-tertiary_on-brand` | `{colors.brand-200}` | `neutral-400` | Tertiary text on solid brand backgrounds |
| `text-quaternary_on-brand` | `{colors.brand-300}` | `neutral-400` | Quaternary text on solid brand backgrounds |
| `text-brand-primary` | `{colors.brand-900}` | `neutral-50` | Brand headings |
| `text-brand-secondary` | `{colors.brand-700}` | `neutral-300` | Brand buttons, accented text, subheadings |
| `text-brand-secondary_hover` | `{colors.brand-800}` | `neutral-200` | Brand buttons, hover state |
| `text-brand-tertiary` | `{colors.brand-600}` | `neutral-400` | Lighter accents such as metric-card numbers |
| `text-brand-tertiary_alt` | `{colors.brand-600}` | `neutral-50` | Lighter alternative in dark mode |
| `text-error-primary` | `red-600` | `red-400` | Error semantic text |
| `text-error-primary_hover` | `red-700` | `red-300` | Error text, hover state |
| `text-warning-primary` | `yellow-600` | `yellow-400` | Warning semantic text |
| `text-success-primary` | `green-600` | `green-400` | Success semantic text |
| `text-editor-icon-fg` | `neutral-400` | `neutral-400` | Text-editor icon rest state |
| `text-editor-icon-fg_active` | `neutral-500` | `{colors.white}` | Text-editor icon active state |

Every brand text role except `text-primary_on-brand` **desaturates to neutral in dark mode**. The brand hue is deliberately withdrawn from type on dark surfaces and survives only in fills.

### Foreground Roles

The `--color-fg-*` family covers non-text foreground — icons, status dots, progress fills, chart strokes.

| Token | Light | Dark |
|---|---|---|
| `fg-primary` | `neutral-900` | `{colors.white}` |
| `fg-secondary` | `neutral-700` | `neutral-300` |
| `fg-secondary_hover` | `neutral-800` | `neutral-200` |
| `fg-tertiary` | `neutral-600` | `neutral-400` |
| `fg-tertiary_hover` | `neutral-700` | `neutral-300` |
| `fg-quaternary` | `neutral-400` | `neutral-600` |
| `fg-quaternary_hover` | `neutral-500` | `neutral-500` |
| `fg-white` | `{colors.white}` | `{colors.white}` |
| `fg-brand-primary` | `{colors.brand-600}` | `{colors.brand-500}` |
| `fg-brand-primary_alt` | `fg-brand-primary` | `neutral-300` |
| `fg-brand-secondary` | `{colors.brand-500}` | `{colors.brand-500}` |
| `fg-brand-secondary_alt` | `fg-brand-secondary` | `neutral-600` |
| `fg-brand-secondary_hover` | `{colors.brand-600}` | `neutral-500` |
| `fg-error-primary` | `red-600` | `red-500` |
| `fg-error-secondary` | `red-500` | `red-400` |
| `fg-warning-primary` | `yellow-600` | `yellow-500` |
| `fg-warning-secondary` | `yellow-500` | `yellow-400` |
| `fg-success-primary` | `green-600` | `green-500` |
| `fg-success-secondary` | `green-500` | `green-400` |

`fg-quaternary` is the system's default icon color: it carries the icons in secondary and tertiary buttons, the leading icon in `{component.input}`, the glyph in `{component.nav-item}`, the sort affordances in `{component.table}`, and the avatar fallback inside `{component.tag}`.

### Border Roles

The `--color-border-*` family. The same values back `ring-` and `outline-` utilities, which is what makes the system's ring-as-border technique possible.

| Token | Light | Dark | Documented usage |
|---|---|---|---|
| `border-primary` | `neutral-300` | `neutral-700` | High contrast — input fields, button groups, checkboxes |
| `border-secondary` | `neutral-200` | `neutral-800` | The most-used default — file uploaders, cards, tables, dividers |
| `border-secondary_alt` | `rgb(0 0 0 / 0.1)` | `neutral-800` | Alpha-transparent; used exclusively for floating menus |
| `border-tertiary` | `neutral-100` | `neutral-800` | Very subtle dividers, chart axis lines |
| `border-brand` | `{colors.brand-500}` | `{colors.brand-400}` | Active states such as focused input fields |
| `border-brand_alt` | `{colors.brand-600}` | `neutral-700` | Switches to gray in dark mode |
| `border-error` | `red-500` | `red-400` | Error state borders |
| `border-error_subtle` | `red-300` | `red-500` | Lower-contrast error borders |

`border-secondary_alt` is the only role in the system authored as an alpha value rather than a palette reference in light mode, which is why it has no entry in the frontmatter color map.

### Utility Ramps

Fourteen eight-step ramps — `blue`, `brand`, `neutral`, `red`, `yellow`, `green`, `orange`, `indigo`, `fuchsia`, `pink`, `purple`, `sky`, `slate`, `emerald` and `amber`. In light mode each step maps one-to-one onto the same-numbered base palette step. In dark mode the ramp **inverts**: `utility-*-50` takes base `950`, `utility-*-100` takes `900`, and so on down to `utility-*-700` taking `300`.

Two ramps break the pattern:

- **`utility-neutral-*`** runs ten steps rather than eight, from `50` to `900`, and its dark inversion collapses `200` and `300` onto the same `neutral-700`.
- **`utility-brand-*`** carries a parallel `_alt` series from `utility-brand-50_alt` to `utility-brand-900_alt`. In light mode `_alt` is identical to the plain step; in dark mode it re-points to the **neutral** utility ramp. This is the mechanism by which brand-tinted surfaces go grayscale on dark without any component knowing.

The ramps exist to serve the badge family, which is their only full consumer.

### Component-Specific Roles

A set of roles named for one consumer rather than a generic slot.

- **`focus-ring`** — `{colors.brand-500}` in both modes. The universal focus indicator.
- **`focus-ring-error`** — `red-500` in both modes.
- **`featured-icon-light-fg-*`** — `{colors.brand-600}` / `red-600` / `neutral-500` / `green-600` / `yellow-600` in light; the `200` step of each ramp in dark.
- **`icon-fg-brand`** — `{colors.brand-600}` light, `neutral-400` dark.
- **`icon-fg-brand_on-brand`** — `{colors.brand-200}` light, `neutral-400` dark.
- **`footer-button-fg` / `footer-button-fg_hover`** — `{colors.brand-200}` to `{colors.white}` in light; `neutral-300` to `neutral-100` in dark. **Declared but consumed by nothing** — the system defines no footer component.
- **`slider-handle-bg` / `slider-handle-border`** — `{colors.white}` on `{colors.brand-600}` in light, inverted in dark so the fill becomes brand and the ring becomes ground. Consumed by `{component.slider-handle}`.
- **`toggle-border`** — `neutral-300` light, transparent dark. Consumed by the slim variant of `{component.toggle}` only.
- **`toggle-slim-border_pressed` / `toggle-slim-border_pressed-hover`** — alias `bg-brand-solid` and `bg-brand-solid_hover` in light; transparent in dark.
- **`tooltip-supporting-text`** — `neutral-300` in both modes. Consumed by `{component.tooltip}` and `{component.chart-tooltip}`.
- **`screen-mockup-border`** — `neutral-900` light, `neutral-700` dark. **Declared but consumed by nothing.**
- **`avatar-styles-bg-neutral`** — `{colors.avatar-neutral}` in both modes, authored as a bare space-separated triplet rather than an `rgb()` function. **Declared but consumed by nothing.**
- **`app-store-badge-border`** — `{colors.app-store-border}`, also a bare triplet, consumed by `{component.app-store-button}`. **The dark-mode override misspells the token name**, dropping the final letter of `badge`, so the intended white border never applies and the badge keeps its light value on dark surfaces.

### Partner Brand Colors

Three identities are hard-coded outside the token layer, because a themeable value would be wrong for a third-party mark:

- Facebook — `{colors.social-facebook}`, pressing to `{colors.social-facebook-active}`
- Dribbble — `{colors.social-dribbble}`, pressing to `{colors.social-dribbble-active}`
- Apple — `{colors.black}`

## Typography

### Font Family

The system declares three family tokens:

- **`--font-body`** — Inter first, then the platform UI stack, then a generic sans fallback.
- **`--font-display`** — an **identical stack** to `--font-body`.
- **`--font-mono`** — a system-monospace stack led by `ui-monospace` and `Roboto Mono`.

Inter is loaded as a variable font with optical sizing and italics across a **400–700 weight axis**, preceded by preconnect hints to the font host. Nothing in the system asks for a weight outside that axis except one prose rule discussed below.

`--font-body` is applied globally to the root and body together with a typographic hygiene block: grayscale antialiasing, contextual ligatures, and normal kerning.

The body stack opens with a `var()` lookup on an undefined `--font-inter` variable, so it always falls through to the literal Inter name. Supplying that variable is the intended hook for swapping the family without editing the token. (inferred — basis: the variable is referenced in the stack but declared nowhere in the system.)

**`--font-display` is defined but never used as a utility.** Because it is identical to `--font-body`, nothing is lost visually — but the token implies a display/body split the system does not actually have. `--font-mono` is used in exactly one place, on an inline command sample.

### Hierarchy

The size scale is the axis the frontmatter flattens. Sizes are declared as multiples of a single spacing unit rather than as literal pixels, and that unit is never overridden, so every step lands on a 4px grid. Line heights are declared in the same unit; tracking is declared only where it applies.

| Size token | Size | Line height | Tracking | Where it lands |
|---|---|---|---|---|
| `--text-xs` | 12px | 18px | — | Badge and tag labels, tooltip title and body, table column headers, chart legends |
| `--text-sm` | 14px | 20px | — | The workhorse — button labels, small inputs, field labels, hint text, nav items, table cells, pagination |
| `--text-md` | 16px | 24px | — | Larger button labels, default and large inputs, nav menu items, prose body |
| `--text-lg` | 18px | 28px | — | Lead paragraphs, large loading-indicator labels |
| `--text-xl` | 20px | 30px | — | Prose h3, blockquote paragraphs, extra-large avatar initials |
| `--text-display-xs` | 24px | 32px | — | Prose h2, largest avatar initials, small progress-circle values |
| `--text-display-sm` | 30px | 38px | — | Prose h1, product page headlines |
| `--text-display-md` | 36px | 44px | **-0.72px** | Page headline at base width |
| `--text-display-lg` | 48px | 60px | **-0.96px** | Page headline at mid width; the two smaller pin-input slots |
| `--text-display-xl` | 60px | 72px | **-1.2px** | Page headline at wide width; the largest pin-input slot |
| `--text-display-2xl` | 72px | 90px | **-1.44px** | **Defined but unused** — no component or page reaches it |

The frontmatter pairs these sizes with the weights they actually carry, which is why entries such as `{typography.sm-regular}`, `{typography.sm-medium}` and `{typography.sm-semibold}` share a size but differ in weight. Size and weight are genuinely independent axes here: the scale token sets size and line height, and a separate weight class sets weight. Display steps are documented at weight 600 because every heading that uses them is semibold; the pin-input is the one exception, rendering `{typography.display-lg}` and `{typography.display-xl}` sizes at weight 500.

Tracking follows a consistent **-0.02em ratio** at every step where it is applied. (inferred — basis: arithmetic relating each declared tracking value to its own font size.)

Because nothing in the system reaches the largest step, `{typography.display-2xl}` is recorded at weight 600 to match its display siblings rather than from an observed pairing. (inferred — basis: every other display step is used at weight 600; the size token itself carries no weight.)

The class-merging helper is extended to know all six display sizes, so a display size and a body size are recognised as conflicting utilities. Without that extension, applying `{typography.display-lg}` over `{typography.lg-regular}` would leave both in the class list.

### Weight

Only three weights appear across the component surface, all inside the loaded axis:

| Weight | Role in the system |
|---|---|
| 400 | Running text — prose body, table cells, hint text, input values, prose links |
| 500 | The labelling weight — field labels, hint emphasis, badge and tag text, pagination items, date cells, progress values, checkbox and toggle labels |
| 600 | The emphasis weight — all button labels, every heading, tab labels, nav items, table column headers, tooltip titles, avatar initials |
| 700 | Confined to prose inline code and prose heading `<strong>` |

Light, thin, extralight, extrabold and black weights are never used. Prose additionally sets heading `<strong>` to 900, 800, 700 and 700 for h1 through h4 — **900 and 800 exceed the loaded axis** and will render as synthesized or clamped weights rather than true cuts.

### Long-Form Prose

The system ships a hand-authored long-form stylesheet scoped to `.prose`, replacing the stock typography plugin defaults and wiring every value to semantic roles rather than to plugin-specific variables. It is a substantial body of styling in its own right.

- Body color is `text-tertiary`; headings take `text-primary`; **links also take `text-tertiary`**, not a brand color — prose links are distinguished by underline alone.
- The base heading ramp is h1 `{typography.display-sm}`, h2 `{typography.display-xs}`, h3 `--text-xl`, h4 `--text-lg`, all at weight 600 — the two largest steps pair size and weight exactly as the frontmatter records them.
- A `.md:prose-lg` modifier shifts the whole ramp up one step at the primary breakpoint: h1 to `--text-display-md`, h2 to `--text-display-sm`, h3 to `--text-display-xs`, h4 to `--text-xl`, and body to `--text-lg`.
- Blockquotes carry a 2px left border in `fg-brand-primary_alt` — **the one place brand color enters prose** — with the paragraph at `{typography.xl-medium}`, italic, and CSS-generated open and close quotes.
- Two modifiers strip that border: `.prose-centered-quote` and `.prose-minimal-quote`.
- Inline code is `{typography.code-inline}` over a `bg-secondary` fill with a `{rounded.md}` corner and a one-pixel box-shadow hairline in `border-secondary`; the backtick pseudo-elements are blanked so no quotes render.
- Prose images take `{rounded.xl}` corners and cover-fit.
- Prose links are underlined at a three-pixel offset and take a `{rounded.sm}` two-pixel focus ring on `:focus-visible`.

## Layout

### Spacing System

- **Base unit:** a single four-pixel unit governs the whole scale and is never overridden.
- **The system declares no named spacing tokens.** Components address the numeric step scale directly — `{spacing.3}` as `px-3`, `{spacing.6}` as `gap-6`, and so on. The frontmatter spacing map records the steps in active use; the system itself names none of them.
- Half-steps are used freely and deliberately, not as escapes: `py-0.75` on small tags, `px-1.25` through `px-4.5` across buttons and inputs, `size-1.25` on the date-picker event dot, and a one-and-a-half-pixel inset on the large avatar border.
- **Page gutter:** `{spacing.4}` below the primary breakpoint, `{spacing.8}` at and above it. The same pairing appears on `{component.section-divider}`, `{component.marketing-header}`, `{component.header-navigation}` and full-page layouts — it is the closest thing the system has to a layout constant.
- **Section rhythm:** the one vertical band treatment in the system runs `{spacing.16}` below the primary breakpoint and `{spacing.24}` at and above. No section-spacing token exists to name it.

### Grid & Container

- **`--max-width-container`, 1280px** — the single layout token in the theme, emitted as `max-w-container`. Every full-width rail in the system uses it.
- Content columns are constrained locally rather than by a grid: `max-w-3xl` on headline blocks, `max-w-xl` on supporting paragraphs, `max-w-lg` on empty states, `max-w-xs` on `{component.tooltip}`, a 400px cap on `{component.slideout-menu}`, and a 248px width on `{component.dropdown-popover}`.
- Layout is **flexbox-first**. No CSS Grid utility appears anywhere in the component surface; multi-column arrangements are flex rows with `gap`.
- Application sidebars size from a CSS variable rather than a fixed class, so the consumer sets `{component.sidebar}` width per instance instead of the system fixing it.

### Whitespace Philosophy

Space is distributed through `gap` on flex containers rather than through margins — `gap-0.5` through `gap-8` account for nearly all internal rhythm, and vertical margin appears almost exclusively inside prose. Spacing steps up at the primary breakpoint in a consistent doubling-ish pattern: `gap-8` to `gap-12`, `gap-4` to `gap-6`, `{spacing.4}` to `{spacing.8}`, `{spacing.4}` to `{spacing.6}`. (inferred — basis: the same base-then-step-up pairing recurs across page layouts, the slideout body, header and footer, and all four gutter sites; the system states no policy.)

## Elevation & Depth

A seven-step neutral ramp plus two skeuomorphic composites. All shadows are pure black at low alpha except the mockup set, which uses a slightly blue-black.

| Token | Value | Use |
|---|---|---|
| `--shadow-xs` | `0px 1px 2px rgba(0,0,0,0.05)` | `{component.input}`, `{component.textarea}`, the `{component.table}` container, `{component.badge-modern}`, minimal tabs, the floating header |
| `--shadow-sm` | `0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | The `{component.toggle}` knob, the selected bordered tab |
| `--shadow-md` | `0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.06)` | `{component.slider-handle}` |
| `--shadow-lg` | `0px 12px 16px -4px rgba(0,0,0,0.08), 0px 4px 6px -2px rgba(0,0,0,0.03), 0px 2px 2px -1px rgba(0,0,0,0.04)` | `{component.tooltip}`, `{component.dropdown-popover}`, the progress value bubble, the mobile nav sheet |
| `--shadow-xl` | `0px 20px 24px -4px rgba(0,0,0,0.08), 0px 8px 8px -4px rgba(0,0,0,0.03), 0px 3px 3px -1.5px rgba(0,0,0,0.04)` | `{component.slideout-menu}` |
| `--shadow-2xl` | `0px 24px 48px -12px rgba(0,0,0,0.18), 0px 4px 4px -2px rgba(0,0,0,0.04)` | The highest elevation the system actually reaches |
| `--shadow-3xl` | `0px 32px 64px -12px rgba(0,0,0,0.14), 0px 5px 5px -2.5px rgba(0,0,0,0.04)` | **Defined but unused** |
| `--shadow-skeuomorphic` | `0px 0px 0px 1px rgba(0,0,0,0.18) inset, 0px -2px 0px 0px rgba(0,0,0,0.05) inset` | An inset hairline over an inset bottom bevel, with no outer shadow at all |
| `--shadow-xs-skeuomorphic` | the skeuomorphic pair composed with `--shadow-xs` | **The signature control treatment** — primary, secondary and destructive buttons, `{component.button-utility}`, `{component.social-button}`, and the dark and modern featured icons |

**Defined but unused:** five `--shadow-modern-mockup-*` composites (inner and outer, at three and two sizes respectively) and `--drop-shadow-iphone-mockup`. The device-mockup asset the last of these was clearly written for exists in the system but applies no shadow of its own.

The depth model layers three separate mechanisms, and most surfaces combine at least two:

1. **Ring-as-border.** An inset one-pixel ring substitutes for `border` throughout, so the hairline never consumes layout box and never shifts a layout when it appears. It carries the outline on `{component.input}`, `{component.table}`, badges, `{component.checkbox}`, `{component.radio-button}`, `{component.featured-icon-modern}` and `{component.dropdown-popover}`.
2. **The skeuomorphic bevel.** `--shadow-xs-skeuomorphic` gives solid controls an inset top hairline and a two-pixel inset bottom edge — a pressed-metal read achieved with no outer shadow whatsoever.
3. **The masked inner border gradient.** Solid fills add a one-pixel inner rule in white at 12% opacity, masked to fade out toward the bottom. This is what separates a brand-solid surface from a flat fill, and it is the detail most often lost when the recipe is applied partially.

The `modern-neue` featured-icon theme carries the most elaborate single shadow in the system — a seven-layer composite including a negative-offset inset highlight, written inline rather than tokenised.

### Decorative Depth

- **Background patterns** — four SVG patterns named `circle`, `square`, `grid` and `grid-check`, each at three sizes. The `grid` pattern renders a 768-square field of one-pixel lines on a 48px pitch, colored from `border-secondary` and radially masked so it fades at the edges.
- **`grid-check` is not theme-aware.** It hard-codes `#D0D5DD` for its lines and `#F2F4F7` for its filled cells instead of inheriting `currentColor` the way its `grid` sibling does, so it will not respond to dark mode. These two values are the clearest case in the system of a color escaping the token layer.
- **Illustrations** — four line illustrations named `box`, `cloud`, `documents` and `credit-card`, each at three sizes, used by empty states.
- **`{component.avatar}` contrast border** — a half-pixel outline at 16% black with a negative offset, plus, above the smallest size, a masked white inner border at 32% that fades through the vertical middle so the image never appears to float.
- Further decorative assets — a QR code, a credit card, a device mockup and a rating-star row — sit alongside the pattern and illustration sets.

## Shapes

### Border Radius Scale

Ten tokens, authored in `rem` except for the zero and pill ends of the scale.

| Token | Use |
|---|---|
| `{rounded.none}` | Underline and line tab variants, which must square off against their rule |
| `{rounded.xs}` | The smallest step; effectively unused |
| `{rounded.sm}` | **Defined but unused as a class** — reached only through the prose link focus ring |
| `{rounded.default}` | The bare `rounded` utility — small checkboxes, link-type buttons |
| `{rounded.md}` | Color and modern badges, `{component.dropdown-item}`, `{component.nav-item}`, medium checkboxes, `{component.progress-bar}` |
| `{rounded.lg}` | **System default** — every button size, `{component.input}`, `{component.textarea}`, `{component.dropdown-popover}`, `{component.tooltip}`, `{component.pagination-item}`, minimal tabs |
| `{rounded.xl}` | The `{component.table}` container, `{component.file-upload}` drop zone and rows, the bordered tab container at wide widths, prose images |
| `{rounded.2xl}` | The floating `{component.marketing-header}` bar at wide widths |
| `{rounded.3xl}` | **Defined but unused** |
| `{rounded.full}` | `{component.avatar}` by default, `{component.radio-button}`, the `{component.toggle}` track and knob, pill badges, light/gradient/outline featured icons, `{component.date-cell}`, `{component.dot-icon}` |

**Arbitrary radii sit alongside the scale, and they are deliberate rather than drift.** Each is a one-pixel inset companion to a scale value, so that a `before:` inner border sits concentrically inside its parent instead of bunching at the corners:

- `rounded-[7px]` is the inner-border partner to `{rounded.lg}`. It appears on every button size, on `{component.social-button}` and `{component.app-store-button}`, and as the squared-off fallback corner of `{component.avatar}`.
- The dark featured-icon theme pairs each size with its inset partner: `{rounded.md}` with 5px, `{rounded.lg}` with 7px, 10px with 9px, and `{rounded.xl}` with 11px.
- The `modern-neue` featured-icon theme runs its own even-numbered ladder — 8 with 4, 10 with 6, 12 with 8, 14 with 10.

### Iconography & Illustration Assets

- The system pairs with a line-style icon library of roughly 1,100 glyphs, a file-type icon set, and a larger commercial set offering four stylistic variants.
- **Icon sizing convention:** three steps — `size-4`, `size-5` and `size-6`. `size-5` is the component default and is the shared icon class on every button.
- **Stroke weight is size-compensated.** Icons dropped to `size-4` take a `2.25px` stroke to hold optical weight against the 20px default. Navigation chevrons go heavier still, at `2.5px` and `2.625px`, because they sit next to semibold labels.
- **Two icon-passing conventions.** An icon may be passed as a component reference, which is preferred, or as a rendered element — in which case it **must** carry a `data-icon` attribute so the parent's descendant selectors can size and color it. An element passed without that attribute silently loses all inherited icon styling.
- **Brand asset inventory:** payment marks, social marks, integration marks and two wordmark lockups. These hard-code third-party brand values by necessity and are explicitly outside the token discipline.
- **Photography** appears only as `{component.avatar}` images, which cover-fit inside an overflow-hidden rounded container across all six avatar sizes. The system ships no photographic assets of its own.

## Components

The component surface divides into five kinds: primitives, composed application patterns, foundational assets and icons, site chrome, and decorative pieces. Variants are organised through a no-op helper that exists purely so tooling can see inside style objects and sort the classes within them; the merge helper it pairs with is a Tailwind class merger extended to understand the display type scale.

The frontmatter records each component's **default configuration**. Where a component has a size ladder, the ladder lives in the tables below.

### Navigation

**`{component.marketing-header}`** — 72px tall, rising to 80px at the primary breakpoint. In its floating mode it shortens to 64px and 76px and becomes a detached bar: `{rounded.2xl}` corners, a `bg-primary` fill, `--shadow-xs`, and a one-pixel ring in `border-secondary_alt`. The inner rail is `max-w-container` with an asymmetric mobile gutter — `{spacing.4}` leading, `{spacing.3}` trailing — that accommodates the menu button. The wordmark swaps by width: the full lockup below the primary breakpoint and again at wide widths, the minimal mark in between.

**`{component.nav-menu-item}`** — `{typography.md-semibold}` in `text-secondary`, with an inner span carrying half-step padding for optical balance and a chevron that rotates 180 degrees when its menu expands.

**`{component.header-navigation}`** — the application-shell counterpart, a `max-w-container` rail with a 64px secondary row.

**`{component.nav-item}`** — the sidebar row. `bg-primary` at rest, `bg-secondary` when selected, with hover states one step deeper in each case. The label is `{typography.sm-semibold}` in `text-secondary`; the icon is `size-5` in `fg-quaternary`. Nested children indent to `pl-10` rather than nesting visually.

**`{component.sidebar}`** — five variants: simple, slim, dual-tier, section-dividers and sections-subheadings. All are full-height `bg-primary` with `{spacing.4}` content padding stepping to `{spacing.5}` at wide widths, and all size their width from a CSS variable rather than a fixed class.

### Buttons

**`{component.button-primary}`** and its siblings are the most fully specified part of the system. Every size shares `{rounded.lg}`, weight 600, the house transition, and a two-pixel focus outline offset two pixels out. The default size is the second step.

| Size | Padding | Type | Icon-only padding | Icon override |
|---|---|---|---|---|
| `xs` | 6px 10px | `{typography.sm-semibold}` | 8px | `size-4` at a 2.25px stroke |
| `sm` | 8px 12px | `{typography.sm-semibold}` | 8px | — |
| `md` | 10px 14px | `{typography.sm-semibold}` | 10px | — |
| `lg` | 10px 16px | `{typography.md-semibold}` | 12px | — |
| `xl` | 12px 18px | `{typography.md-semibold}` | 14px | — |

Nine color variants:

- **`{component.button-primary}`** — a `bg-brand-solid` fill with `{colors.white}` text, `--shadow-xs-skeuomorphic`, a transparent inset ring, and the masked white inner border. Icons ride at 60% white and lift to 70% on hover, so the glyph never competes with the label.
- **`{component.button-primary-active}`** — the pressed and loading state, deepening the fill one ramp step.
- **`{component.button-secondary}`** — a `bg-primary` fill with `text-secondary`, the same skeuomorphic shadow, and a visible inset ring in `border-primary`.
- **`{component.button-tertiary}`** — no fill and no ring; `text-tertiary` with a hover fill only.
- **`{component.button-link}`** — padding stripped entirely and justification normalised. The label carries an underline with a transparent decoration color, so the rule appears only on hover. Underline offset scales with size, three pixels at the small steps and four at the large.
- **`{component.button-destructive}`** — mirrors the neutral trio against `bg-error-solid` and `border-error_subtle`, and swaps the focus ring to the error variant. Primary, secondary and tertiary destructive forms all exist.

The loading state renders an inline two-circle spinner — a 30%-opacity track under a spinning arc — and hides sibling content, or keeps the label visible when asked to. Nested inside an input group, a button picks up `--shadow-xs` and squares off the joined edge.

**There is no separate link component.** Links are buttons with an `href`, which swaps the underlying element while keeping every visual variant available. This is why `{component.button-link}` is a color rather than a component.

**`{component.button-utility}`** — icon-only, two sizes, secondary and tertiary colors, foreground in `fg-quaternary`, with an optional built-in tooltip.

**`{component.social-button}`** — two sizes and three themes: full partner color, monochrome, and neutral. `{component.social-button-active}` deepens the partner color on press. Its base class string references disabled foreground tokens that **no longer exist in the system**, a leftover from the generation that had dedicated disabled colors; those classes generate nothing.

**`{component.app-store-button}`** — a `{colors.black}` fill with a one-pixel ring in `app-store-badge-border` and the arbitrary 7px corner shared with the button family. An outline variant exists alongside it.

A close button and a button group complete the family.

### Inputs & Forms

**`{component.input}`** — the wrapper carries `{rounded.lg}`, a `bg-primary` fill, `--shadow-xs` and a one-pixel inset ring in `border-primary`, transitioning on shadow alone. Focus thickens the ring to two pixels in `border-brand`; invalid drops it to `border-error_subtle`; invalid-and-focused becomes two pixels in `border-error`. The default size is the middle step.

| Size | Padding | Type | Leading icon | With leading icon | With trailing icon |
|---|---|---|---|---|---|
| `sm` | 8px 12px | `{typography.sm-regular}` | `size-4` at 2.25px stroke, inset 12px | `pl-9` | `pr-9` |
| `md` | 8px 12px | `{typography.md-regular}` | `size-5`, inset 12px | `pl-10` | `pr-9` |
| `lg` | 10px 14px | `{typography.md-regular}` | `size-5`, inset 14px | `pl-10.5` | `pr-9.5` |

The input element itself is transparent, so ring and fill live entirely on the wrapper — and autofill is explicitly re-styled to preserve both the corner and the text color, which browsers otherwise override.

**`{component.textarea}`** — the same ring, focus and invalid grammar as `{component.input}`. Its resize grip is a base64-inlined SVG generated at runtime and handed two **hard-coded** colors, `#D5D7DA` for light and `#373A41` for dark, selected by a dark variant on the resizer pseudo-element. Neither value corresponds to any token in the system.

**`{component.label}`** — `{typography.sm-medium}` in `text-secondary`, with a required marker in `text-brand-tertiary` and an error flip driven by the group's invalid state rather than by a prop.

**`{component.hint-text}`** — `{typography.sm-regular}` in `text-tertiary`, dropping to `{typography.xs-regular}` at the small size or when an ancestor declares a small input size.

**`{component.checkbox}`** — 16px at the small size and 20px at the medium, with `{rounded.default}` giving way to `{rounded.md}` at the larger size. `{component.checkbox-active}` fills `bg-brand-solid` and matches the ring to it. Check and indeterminate marks are separate inline SVGs cross-faded by opacity, both stroked at two pixels with round caps and joins.

**`{component.radio-button}`** — the same fill grammar as the checkbox at 16px and 20px, always `{rounded.full}`; the inner dot is 6px or 8px in `fg-white`, also cross-faded by opacity rather than scaled.

**`{component.toggle}`** — two geometries. The default runs 20 by 36 pixels at the small size and 24 by 44 at the medium, with the knob inset by a half-step. The slim variant runs 16 by 32 and 20 by 40 with no padding, so the knob overhangs the track. The track is `bg-tertiary` at rest and `{component.toggle-active}` fills `bg-brand-solid`. The knob carries a **hand-authored inline transition** that splits motion timing from color timing — 150ms ease-in-out for transform and translation, 100ms linear for border and background — which is the only place in the system where a component overrides the house curve for part of its own animation.

**`{component.slider-handle}`** — a 24px circle on a 8px `{rounded.full}` rail; the rail is `bg-quaternary` with a `bg-brand-solid` fill, the handle takes `--shadow-md` and a two-pixel inset ring, and the cursor is set to grab. The value bubble above it is a `{rounded.lg}` card with `--shadow-lg` and a `border-secondary_alt` ring.

**`{component.pin-input}`** — the widest size ladder in the system, six steps from 36px slots up to 96px, with type climbing from `{typography.sm-regular}` to `{typography.display-xl}` at weight 500. Placeholder digits sit at half opacity, and the caret is a two-pixel bar in `fg-brand-primary` driven by the blink animation.

**`{component.file-upload}`** — a `{rounded.xl}` drop zone over `bg-primary` with an inset ring, filling `bg-secondary` when disabled; file rows repeat the same shape. The status line pairs a `size-4` icon with matching semantic text in the success, quaternary or error foreground.

**`{component.select-item}`** — item padding runs 8px with asymmetric horizontal insets at the small size, even at the medium, and 10px by 14px at the large; icons step from `size-4` to `size-5`. The family covers select, combobox, multi-select, tag-select and a native fallback.

Further input variants cover dates, files, groups, numbers, payments and tags, alongside a form wrapper.

### Cards & Containers

**`{component.table}`** — a `{rounded.xl}` container over `bg-primary` with `--shadow-xs` and an inset ring, clipping its contents. `{component.table-header}` sits on `bg-secondary` with labels in `{typography.xs-semibold}` and `text-quaternary`. The header rule and every row separator are drawn as `::after` pseudo-elements one pixel tall rather than as borders, so they survive the container's clipping — and the last row's separator is explicitly hidden. `{component.table-cell}` is `{typography.sm-regular}` in `text-tertiary`, with row hover filling `bg-secondary`. The card header above the table stacks vertically below the primary breakpoint. The whole grid scrolls horizontally rather than reflowing.

**`{component.modal}`** — the overlay is `bg-overlay` at 70% with a six-pixel backdrop blur, bottom-aligned on narrow screens with a clamped bottom inset and centered above. Entry runs 300ms ease-out with a fade and a 95% zoom-in; exit runs 200ms ease-in with the inverse. The panel rounds only below the small breakpoint, since above it the panel floats free.

**`{component.slideout-menu}`** — right-anchored at 400px maximum width with `--shadow-xl`, over the same 70% overlay, with a leading inset that keeps the underlying page partly visible. The footer rule is an inset box-shadow rather than a border, so it does not shift the footer's height.

**`{component.dropdown-popover}`** — 248px wide with `{rounded.lg}`, `--shadow-lg` and a `border-secondary_alt` ring, transform-origin anchored to the trigger. `{component.dropdown-item}` sits inside a small gutter so its hover fill insets from the popover edge rather than touching it. Separators are one-pixel `border-secondary` rules. Fourteen further dropdown compositions build on this base — account cards at three sizes, avatar, breadcrumb, integration, two search forms, three button forms and two icon forms.

**`{component.tooltip}`** — `{rounded.lg}` over `bg-primary-solid`, with vertical padding that grows when a description is present. The title is `{typography.xs-semibold}` in `{colors.white}`; the description is `{typography.xs-medium}` in `tooltip-supporting-text`. It opens after 300ms and closes immediately, offset six pixels from its trigger. Corner placements receive a compensating cross-offset of twelve pixels in the opposite direction so the bubble reads as balanced against the trigger rather than hanging off it. The optional arrow is a quadratic-curve SVG rotated by placement.

**Empty state** — a centered column capped at `max-w-lg`, composed from root, icon, illustration, file-type-icon and header parts, defaulting to a modern gray featured icon with a search glyph. It also carries a dual-strip marquee at a four-minute cycle, with the reverse strip offset by half that, and both strips honour reduced-motion preferences.

**`{component.section-divider}`** — a `max-w-container` rail with the standard gutter pair, wrapping a one-pixel `border-secondary` rule.

### Tags / Badges

**`{component.badge-pill}`** and **`{component.badge-modern}`** — three types across twelve colors. The pill type is `{rounded.full}`; the color and modern types take `{rounded.md}`; all three carry an inset ring, and modern adds `--shadow-xs`. Sizes run 2px by 8px, 2px by 10px, and 4px by 12px, all at weight 500. The default is a medium gray pill.

Every colored badge follows one formula against the utility ramps: a **`-50` fill, a `-700` label and a `-200` ring**, with add-on glyphs at `-500` and add-on buttons at `-400` hovering to `-500` over a `-100` fill. Because the ramps invert wholesale in dark mode, this single formula produces correct dark badges with no dark-specific rules anywhere — it is the clearest demonstration of what the ramp layer buys. The modern type breaks the pattern, using neutral roles directly, and its add-on reaches for a raw palette class — one of the few places the system violates its own role-only rule.

Variants add a leading dot, a leading icon, a flag, an image, and a trailing button, plus a grouped form.

**`{component.tag}`** — three sizes, each with **per-affordance padding compensation** so the label stays optically centered whatever the tag carries:

| Size | Base | With checkbox | With avatar | With dot | With count | With close |
|---|---|---|---|---|---|---|
| `sm` | 3px 8px, `{typography.xs-medium}` | `pl-1.25` | `pl-1` | `pl-1.5` | `pr-1` | `pr-1` |
| `md` | 2px 9px, `{typography.sm-medium}` | `pl-1` | `pl-1.25` | `pl-1.75` | `pr-0.75` | `pr-1` |
| `lg` | 4px 10px, `{typography.sm-medium}` | `pl-1.25` | `pl-1.75` | `pl-2.25` | `pr-1` | `pr-1` |

Content gap and count padding scale with them across three half-steps. Selection modes are none, single and multiple, and single-select disallows an empty selection. Sub-parts cover the checkbox, the close affordance, and an avatar — the last a `{rounded.full}` container over `bg-tertiary` with a user glyph fallback in `fg-quaternary`.

**`{component.dot-icon}`** — an SVG circle at 8px or 10px using `currentColor` for both fill and stroke, so it inherits whatever semantic color its context sets.

### Tabs

**`{component.tab}`** — five horizontal types and five vertical, sharing four button forms and differing in the fifth: horizontal adds an underline form, vertical a line form. Labels are weight 600, stepping from `{typography.sm-semibold}` with `size-4` icons to `{typography.md-semibold}` with `size-5`.

Selection treatment differs per type. `{component.tab-active}` in the brand form fills `bg-brand-primary_alt` with `text-brand-secondary`; the gray form fills `bg-primary_hover`; the bordered form fills `bg-primary_alt` with `--shadow-sm`; the minimal form adds an inset ring and `--shadow-xs`; and the underline and line forms draw a **two-pixel rule in `fg-brand-primary_alt`** on the bottom or left edge, squaring their corners to `{rounded.none}` so the rule meets the edge cleanly.

Notably, **hover and selected are styled identically** in five of the ten forms — the system treats hover as a preview of selection rather than a separate state.

The container carries its own chrome: the bordered form wraps in a 10px-cornered `bg-secondary_alt` tray with an inset ring, stepping to `{rounded.xl}` at the primary breakpoint; the minimal form uses `{rounded.lg}` with the same fill and ring.

### Data Display & Feedback

**Featured icons** — six themes across five colors and four sizes, from 32px up to 56px, with glyphs stepping `size-4` through `size-7`.

| Theme | Shape | Treatment |
|---|---|---|
| `{component.featured-icon-light}` | `{rounded.full}` | A secondary-tinted fill with a mid-ramp glyph |
| `gradient` | `{rounded.full}` | A `-200` ring over a `-50` fill, with a solid inner disc |
| `{component.featured-icon-dark}` | `{rounded.md}` to `{rounded.xl}` by size | A solid fill with `--shadow-xs-skeuomorphic` and the masked white inner border |
| `{component.featured-icon-modern}` | `{rounded.md}` to `{rounded.xl}` | `bg-primary` with `--shadow-xs-skeuomorphic` and an inset ring |
| `modern-neue` | its own even-step ladder | `bg-primary_alt` with the seven-layer composite shadow; **only the gray color is implemented — the other four slots are empty** |
| `outline` | `{rounded.full}` | Two concentric two-pixel rings at 30% and 10% alpha of the foreground |

The system's own guidance flags the restriction explicitly: the modern themes are gray-only.

**`{component.avatar}`** — six sizes from 24px to 64px, with initials climbing the type scale from `{typography.xs-semibold}` to `{typography.display-xs}`, always at weight 600. It is `{rounded.full}` by default and falls back to the 7px corner when squared. An optional border adds a `border-secondary_alt` ring plus a size-matched inset. Sub-parts cover an online indicator, a verified tick, an overflow count, an add button and a company icon; companions add a label group and a profile-photo form.

**`{component.progress-bar}`** — an 8px `{rounded.md}` track in `bg-quaternary` with a `fg-brand-primary` fill transitioning at 75ms, the fastest curve in the system. The floating value label is a `{rounded.lg}` card over `bg-primary_alt` with `--shadow-lg`, a `border-secondary_alt` ring and tabular numerals.

**Progress circles** — value text climbing `--text-display-xs` through `--text-display-lg` by size, with a simplified companion form.

**`{component.loading-indicator}`** — three types across four sizes, with the spinner running 32px to 64px and the label at `{typography.sm-medium}` or `{typography.lg-medium}`. The line spinner is a single circle with a dash array and offset tuned to leave a visible arc, stroked in `fg-brand-primary`.

**`{component.pagination-item}`** — 36px squares at `{typography.sm-medium}` in `text-quaternary`, hovering into `bg-primary_hover` with `text-secondary`. A boolean toggles the whole rail between `{rounded.full}` and `{rounded.lg}`. Below the primary breakpoint the numbered rail is replaced by a page-count summary. Base, dot and line forms exist alongside two page-level compositions.

**`{component.date-cell}`** — 40px `{rounded.full}` cells. Range ends round on one side only while the interior fills `bg-active`, and the range edges are feathered with a gradient `::after` that fades into the fill and is suppressed on the first and last cells of each row — so a range that wraps a week boundary reads continuously. `{component.date-cell-active}` fills `bg-brand-solid`; today takes `bg-active` at weight 500; disabled days drop to half-opacity text. Event markers are 5px dots that flip from `fg-brand-primary` to `fg-white` when their day is selected. The family covers a calendar, a range calendar, and single and range pickers.

**Charts** are built on a third-party charting library. `{component.chart-tooltip}` reuses the tooltip grammar exactly — `{typography.xs-semibold}` in `{colors.white}` with rows in `tooltip-supporting-text`. The active dot is a rounded rect filled from `bg-primary` and stroked from `utility-brand-600`; legend entries are `{typography.sm-regular}` in `text-tertiary`. A global reset strips the library's default focus outlines from every chart surface.

**Carousel** is built on a third-party embla-based library and carries no distinct token surface of its own.

## Do's and Don'ts

### Do

- Style with role-named classes — `text-primary`, `bg-primary`, `border-secondary` — never with raw palette classes. The system states this as a hard requirement, not a preference.
- Re-brand by editing the brand ramp and nothing else. The system's claim is that the scale then adapts to both modes on its own through the variable chain, and the role tables above bear that out.
- Supply a complete brand ramp when re-branding — 25 through 950, with contrast ratios checked, even though the 25 step is not currently declared.
- Prefix every React Aria import with `Aria`. The system marks this critical and gives three reasons: it prevents naming collisions with the system's own components, it makes base-component usage visible at the import site, and it keeps the convention uniform.
- Name every file in kebab-case — components, modules, styles, tests and new config files alike.
- Use the house transition, 100ms linear, for hover and color changes. The system describes it as snappy enough to feel responsive without being jarring.
- Express disabled state as a cursor change plus 50% opacity.
- Pass icons as component references. When passing a rendered element instead, include the `data-icon` attribute so the parent's sizing and color selectors still reach it.
- Add `aria-hidden` to decorative icons.
- Keep variant classes inside the sort helper's style objects so tooling can sort and complete inside them.
- Compensate stroke weight when shrinking icons — `size-4` pairs with a 2.25px stroke throughout.
- Pair an inner-border radius one pixel inside its parent's radius whenever adding a masked inner border.

### Don't

- Don't write raw palette classes such as `text-gray-900`, `text-gray-600` or `bg-blue-700`; the system names these three explicitly as the anti-pattern.
- Don't use the removed disabled color tokens — the subtle-background, disabled-text and disabled-ring trio are a prior-generation pattern the system explicitly retired.
- Don't import from React Aria without the prefix.
- Don't use PascalCase or camelCase filenames.
- Don't apply the modern or `modern-neue` featured-icon themes with any color but gray; the other four color slots are empty strings and will render unstyled rather than falling back.
- Don't reach for `{colors.brand-600}` directly when `bg-brand-solid` expresses the intent. The role layer is what makes dark mode work without per-component overrides. (inferred — basis: every dark-mode adaptation operates on roles and utility ramps, never on component classes.)
- Don't add a dark-mode override to a component when the role it already uses inverts on its own. Across the whole component surface, a dark variant appears only where a value genuinely cannot be tokenised — the `{component.textarea}` resize grip and the device mockup's screen image. (inferred — basis: those are the only component files carrying a dark variant; every other dark adaptation happens in the theme layer.)
- Don't reuse the 7px inner-border radius as a standalone corner on a new surface. It exists to sit one pixel inside an eight-pixel parent, and used alone it reads as a slightly wrong `{rounded.lg}`. (inferred — basis: every occurrence is either a pseudo-element inside a `{rounded.lg}` parent, or the avatar's squared fallback.)

## Responsive Behavior

### Breakpoints

Two custom breakpoints are declared alongside the inherited defaults. A hook mirrors the defaults for JavaScript-side queries.

| Token | Width | Origin | Observed use |
|---|---|---|---|
| `--breakpoint-xxs` | 320px | Declared by the system | **No variant appears in any component** |
| `--breakpoint-xs` | 600px | Declared by the system, commented as needing to match a toast library's own breakpoint | **No variant appears in any component** |
| `sm` | 640px | Inherited default | `{component.modal}` centering, button-row direction |
| `md` | **768px** | Inherited default | **The system's primary breakpoint** — gutters, header height, floating-header chrome, nav collapse, the prose ramp, table header direction, pagination mode |
| `lg` | 1024px | Inherited default | Sidebar width activation, wordmark swap, the top headline step |
| `xl` | 1280px | Inherited default | Coincides with `--max-width-container`; available but rarely used |
| `2xl` | 1536px | Inherited default | Available; unused |

The breakpoint hook wraps a media-query listener with an SSR-safe initial value that defaults to true, so server-rendered markup assumes the wide case. It exposes only the five inherited defaults — the two custom breakpoints are unreachable from JavaScript, which is part of why nothing uses them.

### Touch Targets

Measured from the declared geometry rather than from a stated policy:

- `{component.nav-item}` — 36px tall, full row width.
- `{component.pagination-item}` — 36px square.
- `{component.date-cell}` — 40px square.
- `{component.button-primary}` at the middle size — 40px tall overall. The two largest sizes reach 44px and 48px. (inferred — basis: declared padding plus the line-height of the size token; no height is declared on the component.)
- Icon-only buttons at the middle size — 40px square.
- `{component.checkbox}` and `{component.radio-button}` — 16px or 20px for the control itself, but the entire `{component.label}` row is the press target.
- `{component.toggle}` — 20px or 24px tall.
- `{component.avatar}` at the default size — 40px square.

Several controls sit below a 44px square. The system states no minimum target size.

### Focus Behavior

Focus is the system's most uniformly handled surface:

- The ring color is the brand mid-step, identical in both modes; error contexts swap to the error focus ring.
- The house pattern is a two-pixel outline offset two pixels out, on `focus-visible` only — used by buttons, `{component.tab}`, `{component.nav-item}`, `{component.pagination-item}`, `{component.checkbox}`, `{component.radio-button}`, `{component.toggle}` and `{component.avatar}`.
- Inset contexts — tab items and table rows — negate the offset so the ring stays inside the container instead of overlapping a neighbour.
- `{component.input}` and `{component.textarea}` opt out of outlines entirely and express focus by thickening their existing ring, which keeps the field's footprint stable.
- Table cells raise their stacking order on focus so the ring is not clipped by adjacent cells.

### Collapsing Strategy

- **Navigation** collapses below the primary breakpoint: the horizontal nav hides and the trigger appears. The mobile panel is a full-width `bg-primary` sheet with `--shadow-lg`, hidden scrollbars, and items stacked in a tight column.
- **Mobile nav items** become full-bleed rows at `{typography.md-semibold}` with a hover fill, and the section wrapper takes a top rule and generous vertical padding.
- **Gutters** step from `{spacing.4}` to `{spacing.8}` at every container.
- **Type ramps up, not down.** Page headlines run three steps upward across breakpoints and leads run two — the narrow case is the base and wider viewports opt in, rather than large type being scaled down.
- **Prose** switches to its larger ramp at the primary breakpoint.
- **`{component.modal}`** is bottom-anchored on narrow screens and center-anchored from the small breakpoint up.
- **`{component.table}`** never reflows — it scrolls horizontally, and only its card header stacks.
- **`{component.pagination-item}`** rails are replaced by a text summary below the primary breakpoint.
- **Button rows** reverse direction on narrow screens so the primary action sits at the bottom, nearest the thumb.
- **`{component.sidebar}`** is unconstrained below the wide breakpoint and adopts its variable width above.

### Image Behavior

- `{component.avatar}` images cover-fit inside an overflow-hidden rounded container, with an error fallback to initials or a user glyph.
- Prose images are full-width, cover-fit, with `{rounded.xl}` corners.
- The device mockup is a fixed-viewBox SVG using a slice-fit aspect ratio at auto height, and swaps to a dark asset under the dark variant when one is supplied.
- Background patterns are fixed-viewBox SVGs positioned decoratively and made non-interactive.

## Dark Mode

Dark mode is the most heavily engineered part of the system — close to half the token file exists to serve it.

- **Activation** is a `dark-mode` class on the root element, registered as a custom variant that matches the class and all its descendants.
- **The theme provider** supports light, dark and system. It persists an explicit choice to local storage and, in system mode, subscribes to the OS preference and *removes* the stored key so the choice stays reactive rather than freezing at the last resolved value.
- **A blocking inline script** applies the class before first paint to avoid a flash of the wrong theme. **That script reads a different storage key than the provider writes**, so a stored preference is not honoured until the application hydrates — the flash the script exists to prevent still occurs for users who chose a theme explicitly.
- **The inversion happens at the ramp and role layers only.** Because badges are written against utility ramps and everything else against semantic roles, almost no component carries a dark variant.
- **Semantic hues lighten by two steps** for text and one for foregrounds — error, warning and success all move up the ramp — preserving contrast against the dark ground.
- **Brand hue withdraws from type.** Every brand text role except the on-brand variant resolves to a neutral, as does the brand icon foreground. Only the solid family holds its brand value.
- **Brand page bands dissolve.** The two brand section backgrounds collapse onto plain surface roles, so a band that reads as brand-colored in light mode is simply a darker surface in dark mode.
- **Three tokens invert their meaning rather than their value.** The slider handle swaps fill for stroke, and the toggle border family goes fully transparent — in dark mode the toggle's edge is carried by contrast alone.
- The dark block **re-declares the property-namespace mirrors** rather than relying on inheritance. The two sets are not quite symmetric: exactly two mirrors are declared in dark and absent from light — a tertiary border background and a white text color — while no mirror exists in light that dark omits. Separately, the white text color is declared twice inside the light block, once among the text roles and once among the text property mirrors, with identical values.

## Motion & Transitions

- **House transition:** 100ms linear, applied to buttons, nav items, tabs, dropdown items, inputs, icons and table affordances.
- **Timing variance is deliberate and narrow:** 75ms on the progress fill, 100ms as the default, 150ms on the toggle track, 200ms on the label help-icon and on every exit animation, 300ms on modal entry.
- **Enter and exit are asymmetric:** overlays enter at 300ms ease-out and leave at 200ms ease-in, so dismissal feels quicker than appearance.
- **A transition-inheritance utility** lets a child adopt its parent's transition property, duration and timing function, so button icons and checkbox marks animate on exactly the parent's curve without restating it — and without drifting if the parent's curve changes.
- **`--animate-marquee`** — a 60-second linear infinite translation across a full width. Its only consumer overrides the duration to four minutes.
- **`--animate-caret-blink`** — a one-second infinite cycle that steps opacity hard at the midpoint rather than fading, which is what makes it read as a terminal caret.
- **An animation utility plugin** supplies the enter/exit, fade, zoom and slide primitives used by modals, tooltips and dropdowns. Tooltips slide in from the side opposite their placement.
- **A motion library** is available for complex animation beyond the utility set.
- **Reduced motion** is honoured only by the empty-state marquee. There is no global reduced-motion rule.

## Token Architecture & Customization

**Re-branding** is a single-file operation: edit the brand ramp, ideally supplying all twelve steps. Exactly one value must be changed outside the token layer — the document's `theme-color` meta tag, which hard-codes the anchor.

**Why the property-namespace mirror layer exists.** The utility engine resolves `bg-*` from the background-color namespace before falling back to the generic color namespace, `text-*` from the text-color namespace, and so on. By declaring all five namespaces explicitly, the system guarantees that one role name works as `bg-primary`, `text-primary`, `border-primary`, `ring-primary` and `outline-primary` alike — which is precisely what makes an inset ring a drop-in substitute for a border across the whole component surface. (inferred — basis: the five mirror blocks re-export existing roles with no value changes, and components address all five namespaces against the same role names.)

**Plugin surface.** Three plugins extend the utility vocabulary: a typography plugin, a React Aria plugin supplying the placement, expansion and selection variants the components lean on, and an animation plugin supplying the enter/exit primitives.

**Custom variants.** Three beyond the defaults: the dark-mode variant, a `label` variant targeting labelled descendants, and a `focus-input-within` variant that fires when a contained input takes focus.

**Custom utilities.** Two: cross-browser scrollbar suppression, and the transition-inheritance utility described above.

**Global resets.** The system normalises five browser behaviours that would otherwise leak through: the Safari disclosure marker, number-input spinners in both engines, the search-input clear button, and chart focus outlines.

## What the Frontmatter Cannot Carry

Four properties of this system have no representation in the flat schema above, and are recorded here so nothing depends on the frontmatter alone.

- **Border, ring and outline color.** The component property vocabulary covers background and text color only. Since this system draws nearly every hairline as an inset ring rather than a border, the frontmatter cannot express the outline of `{component.input}`, `{component.table}`, `{component.checkbox}`, `{component.badge-modern}`, `{component.dropdown-popover}` or `{component.featured-icon-modern}` — arguably their most characteristic property. The role tables and component entries above carry it instead.
- **Dual-mode values.** Every color key resolves to one value, so the frontmatter carries light mode only. The dark resolutions live in the Background, Text, Foreground and Border role tables, and the inversion rule lives in the Dark Mode section.
- **Semantic roles as colors.** The roles that resolve into the inherited neutral, red, green and yellow ramps have no literal value anywhere in the system — they are indirections onto a palette the system does not restate. They cannot be flattened into a hex map without inventing values, so they appear only as role names.
- **Opacity as state.** Disabled is expressed as 50% opacity, not as a color. There is no `-disabled` entry in the component map because the system deliberately has no disabled color tokens; the absence is the design decision. Likewise there is no `-on-dark` entry, because dark mode is a global class override rather than a per-component variant.

## Iteration Guide

1. Change a token, not a component. If a component needs a value the theme lacks, add the role to both the light block and the dark block, and mirror it into the relevant property namespace — all three, or it will work in one mode and one utility family only.
2. Reference roles by name, not by ramp step: `bg-brand-solid`, not `{colors.brand-600}`. The role layer is what makes dark mode free.
3. Keep variants inside sorted style objects keyed by common, sizes and colors, matching the button family.
4. Build interactive components on React Aria with the prefixed import, and drive state styling from render-prop booleans rather than pseudo-class guesses.
5. Name new files in kebab-case and place them by kind: primitives, composed patterns, foundational assets, site chrome, decorative pieces.
6. Add both a size ladder and a color ladder where the pattern applies — three sizes is the house minimum, five where the component warrants it.
7. When adding a solid-fill surface, carry the full recipe: the skeuomorphic shadow, a transparent inset ring, and the masked white inner border. Partial application reads as a different component family.
8. Document hover and pressed states in the style object. This system encodes hover extensively — unlike disabled, which is uniformly an opacity change.
9. Prefer rings over borders for hairlines so the outline never affects layout, and use pseudo-element rules where a clipping container would otherwise cut a border off.

## Known Gaps

- **No spacing tokens.** The system names no spacing steps; components address the numeric scale directly. There is no named section rhythm — the one vertical band treatment in the system is written inline.
- **No documented photography or illustration direction.** Four line illustrations and four background patterns ship with no usage policy, and no photographic assets exist.
- **No color contrast data.** The system asks for proper contrast ratios when re-branding but records no measured values for the ramp it ships.
- **No animation or easing tokens beyond two keyframes.** Durations and curves are written inline as utility classes; there are no easing or duration variables.
- **No focus-visible policy statement.** The pattern is consistent in code but nowhere written down.
- **No minimum touch-target policy.** Several controls measure 36px.
- **Most composed patterns have no worked usage example.** Sidebars, tables, tabs, charts, date pickers, modals and slideouts are specified but never assembled into a page within the system itself, so composition-level conventions are undocumented.
- **Chart colors are not defined.** Only the active-dot stroke and the tooltip roles are specified; series color assignment is left to the consumer and no categorical palette exists.
- **The system's own documentation drifts from its implementation in three places**: it points at a theme-context module path that no longer matches the file, documents a brand ramp step that is not declared, and documents a subtle secondary background role that is defined nowhere and used by nothing.
- **Four defects are visible in the token layer**: the misspelled dark-mode app-store border token; the storage-key mismatch between the anti-flash script and the theme provider; the social button's reference to disabled foreground tokens that no longer exist; and the non-theme-aware grid-check pattern.
- **Four components use raw palette classes**, contradicting the system's own hard rule — the credit-card asset most heavily, plus the empty-state gradient, the modern badge add-on, and the rating stars.
- **The documented surface is a subset.** A substantially larger component set exists beyond the one specified here, so absence from this document is not evidence that a pattern is undefined.

---

## Audit A — Coverage

**What the frontmatter flattened, and where the discarded facts went.** The schema is single-valued, two levels deep, and has a fixed component property vocabulary; this system is four-layer, dual-mode and ring-heavy. Five kinds of information could not survive the flattening and were relocated rather than dropped:

| Flattened away | Recovered in |
|---|---|
| Dark-mode resolutions of every color role | The Background, Text, Foreground and Border role tables, plus Dark Mode |
| The four-layer indirection chain — base palette, utility ramps, semantic roles, property mirrors | Overview, Utility Ramps, Token Architecture |
| Border / ring / outline color on every component | The role tables, the component entries, and What the Frontmatter Cannot Carry |
| Size ladders — buttons, inputs, badges, tags, tabs, avatars, featured icons, pin inputs, loading indicators | The per-component tables in Components; the frontmatter carries only each component's default configuration |
| The independent size axis of the type scale, and its line heights as authored | The Hierarchy table, which lists the raw size tokens; frontmatter entries pair size with the weight each actually carries |

Two conversions were forced by the schema and are noted here because they are derivations rather than transcriptions: `lineHeight` is unitless, computed as the ratio of the authored line-height to the authored size at each step; and `colors` is hex, converted from the `rgb()` triplets the system authors.

**Deliberately excluded from `colors`.** The map carries only values the system treats as palette. Excluded: the alpha-authored `border-secondary_alt`, which has no hex form; the dark-mode ground and dark resize-grip values, which the single-valued map cannot hold; and the one-off hard-codes in the resize grip and the grid-check pattern, which are documented in prose precisely because they escaped the token layer.

**Excluded from the token maps entirely,** for want of a schema namespace: shadows, font families, breakpoints, animations, the container max-width, and the arbitrary inner-border radii. These are referenced in prose by their own token names — `--shadow-xs`, `--font-body`, `--breakpoint-xxs`, `--animate-marquee`, `--max-width-container` — and are fully specified in Elevation, Font Family, Breakpoints, Motion and Grid respectively. Adding namespaces for them would have extended the schema.

**Sections beyond the template's list**, because the subject has facts with no home in it: Base Colors, Foreground Roles, Utility Ramps, Component-Specific Roles, Partner Brand Colors, Weight, Long-Form Prose, Focus Behavior, Dark Mode, Motion & Transitions, Token Architecture & Customization, and What the Frontmatter Cannot Carry. The last of these exists specifically to hold facts that fit neither part of the document.

**Left thin, with reason.** Whitespace Philosophy and three of the Don'ts are short because the system states no policy — only patterns, which are marked `(inferred)` with their basis. Photography is thin because no photographic assets exist. Grid is thin because there is no grid system; layout is flexbox with local width caps.

**Characterized rather than enumerated.** The icon and brand-asset inventory runs to roughly a hundred files — payment marks, social marks, integration marks and two wordmarks — each an SVG path carrying third-party brand values and no token content. The fourteen dropdown compositions, five sidebar variants, and the country and timezone data modules are named but not individually specified.

## Audit B — Contamination

No content from the template survives. Every color, size, weight, radius, breakpoint, shadow, component name and characterization above derives from the subject system's own source, recorded claim by claim in the Source Trace below. None of the template's hexes, its serif and sans pairing, its named accent hues, its named spacing tokens, its container width, its section rhythm, its token namespaces, or any of its component names appear here. The template's opinions — its claimed brand differentiator, its trinity of surfaces, its surface-alternation pacing rule, its instruction never to document hover — were treated as absent. Where this document offers equivalents, they are derived from the subject: the role-layer discipline, the skeuomorphic recipe, the ramp-inversion mechanism. Iteration Guide point 8 in fact records the opposite of the template's hover rule, because this system encodes hover heavily.

Four overlaps are coincidental and independently sourced:

1. **Inter** — named in the template as a substitute face. It is independently this system's actual and only family, for both body and display.
2. **The word "modern"** — prose in the template; here a literal identifier, naming a badge type and two featured-icon themes.
3. **An 8px and a 12px radius step** — numerically coincident with two template steps. Both are independently declared here, in a ten-step scale with different names, values and distribution.
4. **The section skeleton** — borrowed as instructed, as shape only. Every heading below the top level was rewritten to name this system's concepts.

## Audit C — Sourcing

**Traced.** Every hex, rgb triplet, px value, rem value, weight, radius, shadow, breakpoint, duration, class string, component name, default prop value, occurrence count and defect in this document is recorded in the Source Trace below, against the file and line it came from. Palette hexes are conversions of the authored `rgb()` triplets. Type-scale pixel values are the authored spacing-unit expressions resolved against the base unit, which was verified as never overridden. Occurrence counts — moved out of the prose, since a count is evidence rather than a design claim — are tallies across the component and page surface. Behavioral descriptions of the text, border, foreground and background roles are the system's own wording.

**Marked (inferred), with basis stated inline.** Seven claims: the -0.02em tracking ratio, from arithmetic on four declared pairs; the undefined font-family variable falling through, from the absence of any declaration; the whitespace step-up pattern, from the same pairing recurring at six sites; the purpose of the property-namespace mirror layer, from utility-engine resolution order against the observed five-namespace usage; the 40px button height, from padding plus line-height, since no height is declared; and two Don'ts — avoiding direct ramp-step references and avoiding redundant dark overrides — both from the theme-layer-only inversion pattern and the near-total absence of dark variants in components.

**Defined but unused.** A brand-25 step documented but never declared; the largest display size; the smallest-but-one radius as a class, and the largest radius; the largest shadow; all five mockup shadow composites; the device-mockup drop shadow; the display font family as a utility; both custom breakpoints as variants; both brand section backgrounds; both footer button foregrounds; the screen-mockup border; the neutral avatar background; and a subtle secondary background documented but never declared. The app-store border token is used, but its dark-mode override is unreachable through the spelling defect noted above.

**Deliberately not claimed.** No contrast ratios, no conformance statement, no rationale for the brand hue, no assertion about which components are most used beyond the system's own claim about buttons, and no characterization of how the system looks or feels beyond what the declared values support.

---

## Source Trace

Every claim above, against the file and line it was read from. Paths are relative to the Untitled UI React source tree this document was extracted from, not to this repository. This appendix is self-contained: deleting it from the horizontal rule down removes all sourcing and leaves the document intact.

| Claim | Token or component | Source |
|---|---|---|
| Tokens live in a single Tailwind `@theme` block; no JS config, no token JSON | — | src/styles/theme.css:1 |
| Base palette: brand ramp declared, inherited ramps not redefined | `--color-brand-*` | src/styles/theme.css:124-134 |
| Utility ramp layer | `--color-utility-*` | src/styles/theme.css:141-289 |
| Semantic role layer | `--color-text/bg/border/fg-*` | src/styles/theme.css:291-397 |
| Property-namespace mirror layer | `--background-color-*` etc. | src/styles/theme.css:401-494 |
| Brand ramp authored as rgb() triplets; hex is conversion | `{colors.brand-50}`–`{colors.brand-950}` | src/styles/theme.css:124-134 |
| Interactive anchor | `{colors.brand-600}` | src/styles/theme.css:130 |
| Anchor duplicated as document theme-color meta tag | `{colors.brand-600}` | index.html:8 |
| Dark mode is a class-scoped override block | `.dark-mode` | src/styles/theme.css:497-856 |
| Dark custom variant registration | `dark` variant | src/styles/globals.css:9 |
| Role-classes-only rule stated as MUST | — | CLAUDE.md:697-711 |
| Body and display families resolve identically | `--font-body`, `--font-display` | src/styles/theme.css:3-4 |
| Type scale declared as spacing-unit multiples | `--text-*` | src/styles/theme.css:29 |
| Spacing base unit never overridden | `--spacing` | src/styles/theme.css, src/styles/globals.css (absent) |
| Tracking applied only from display-md up | `--text-display-*--letter-spacing` | src/styles/theme.css:31,35,39,43 |
| Skeuomorphic shadow pair | `--shadow-skeuomorphic` | src/styles/theme.css:74-75 |
| `{rounded.lg}` is the most-used explicit radius — 64 occurrences | `{rounded.lg}` | src/styles/theme.css:59; tally across src/components |
| `{rounded.full}` matches it — 64 occurrences | `{rounded.full}` | src/styles/theme.css:63; tally across src/components |
| React Aria prefix convention marked CRITICAL | — | CLAUDE.md:19-32 |
| Disabled is uniform opacity, replacing prior disabled tokens | — | CLAUDE.md:275-284 |
| Two keyframe animations exist | `--animate-marquee`, `--animate-caret-blink` | src/styles/theme.css:91-113 |
| House transition is 100ms linear | — | CLAUDE.md:259-267 |
| Brand-25 documented as part of a 25–950 scale but never declared | `--color-brand-25` | CLAUDE.md:147-161 (absent from src/styles/theme.css) |
| Base colors block | `transparent`, `{colors.white}`, `{colors.black}` | src/styles/theme.css:115-122 |
| Alpha pair swapped and re-toned in dark | `--color-alpha-white/black` | src/styles/theme.css:501-502 |
| Background roles, light | `--color-bg-*` | src/styles/theme.css:347-376 |
| Background roles, dark | `--color-bg-*` | src/styles/theme.css:708-736 |
| Text roles, light | `--color-text-*` | src/styles/theme.css:291-314 |
| Text roles, dark | `--color-text-*` | src/styles/theme.css:655-677 |
| Text role usage descriptions are the system's own | — | CLAUDE.md:717-738 |
| Foreground roles, light | `--color-fg-*` | src/styles/theme.css:326-345 |
| Foreground roles, dark | `--color-fg-*` | src/styles/theme.css:688-706 |
| Foreground role usage descriptions | — | CLAUDE.md:755-778 |
| Border roles, light | `--color-border-*` | src/styles/theme.css:316-324 |
| Border roles, dark | `--color-border-*` | src/styles/theme.css:679-686 |
| Same values back ring- and outline- utilities | — | CLAUDE.md:742 |
| Utility ramps, light, fourteen families | `--color-utility-*` | src/styles/theme.css:141-289 |
| Utility ramps invert in dark | `--color-utility-*` | src/styles/theme.css:504-653 |
| Neutral utility ramp runs ten steps; dark collapses 200 and 300 | `--color-utility-neutral-*` | src/styles/theme.css:538-539 |
| Brand `_alt` series re-points to neutral in dark | `--color-utility-brand-*_alt` | src/styles/theme.css:516-533 |
| Badge family is the ramps' only full consumer | `{component.badge-pill}` | src/components/base/badges/badges.tsx:8-68 |
| Component-specific roles, light | focus ring, slider, toggle, tooltip | src/styles/theme.css:378-397 |
| Component-specific roles, dark | same set | src/styles/theme.css:738-757 |
| App-store border authored as a bare triplet | `{colors.app-store-border}` | src/styles/theme.css:379 |
| Neutral avatar background authored as a bare triplet | `{colors.avatar-neutral}` | src/styles/theme.css:380 |
| App-store border consumed by the badge button | `{component.app-store-button}` | src/components/base/buttons/app-store-buttons.tsx:11 |
| Dark-mode app-store border token misspelled | `--color-app-store-badg-border` | src/styles/theme.css:738 |
| Slider handle roles consumed | `{component.slider-handle}` | src/components/base/slider/slider.tsx:55 |
| Partner brand hexes hard-coded outside the token layer | `{colors.social-facebook}`, `{colors.social-dribbble}` | src/components/base/buttons/social-button.tsx:30-41 |
| Three family tokens | `--font-body`, `--font-display`, `--font-mono` | src/styles/theme.css:3-5 |
| Inter loaded as a variable font, 400–700 axis, with preconnects | — | index.html:10-12 |
| Global font application and typographic hygiene block | `--font-body` | src/styles/globals.css:31-40 |
| Mono family used once, on an inline command sample | `--font-mono` | src/pages/home-screen.tsx:24 |
| Type scale sizes, line heights, tracking | `--text-*` | src/styles/theme.css:8-43 |
| Display-sm used for product headlines | `--text-display-sm` | src/pages/home-screen.tsx:17 |
| Display-md as page headline base | `--text-display-md` | src/pages/not-found.tsx:15 |
| Class merger extended to know the display sizes | — | src/utils/cx.ts:3-9 |
| Weight tallies: 500 ×127, 600 ×69, 700 ×3, 400 ×1 | — | tally across src/components, src/pages |
| Prose heading `<strong>` set to 900/800/700/700 | `.prose` | src/styles/typography.css:149-163 |
| Prose stylesheet wired to semantic roles | `.prose` | src/styles/typography.css:1-23 |
| Prose links take `text-tertiary`, not a brand color | `.prose` | src/styles/typography.css:5 |
| Prose ramp shifts up one step at the primary breakpoint | `.md:prose-lg` | src/styles/typography.css:333-360 |
| Blockquote 2px brand-alt border, weight 500 italic, generated quotes | `.prose` | src/styles/typography.css:76-99 |
| Two blockquote modifiers strip the border | `.prose-centered-quote`, `.prose-minimal-quote` | src/styles/typography.css:247-271 |
| Inline code weight 700 with fill, radius and box-shadow hairline | `{typography.code-inline}` | src/styles/typography.css:230-245 |
| Prose images take `{rounded.xl}` and cover-fit | `.prose` | src/styles/typography.css:168-176 |
| Prose link focus ring reaches `{rounded.sm}` | `{rounded.sm}` | src/styles/typography.css:215-223 |
| Half-step spacing: tag vertical padding | `{component.tag}` | src/components/base/tags/tags.tsx:75 |
| Half-step spacing: date-picker event dot | `{component.date-cell}` | src/components/application/date-picker/cell.tsx:97 |
| Half-step spacing: avatar large border inset | `{component.avatar}` | src/components/base/avatar/avatar.tsx:73 |
| Page gutter pair on the divider | `{component.section-divider}` | src/components/shared-assets/section-divider.tsx:6 |
| Page gutter pair on the marketing header | `{component.marketing-header}` | src/components/marketing/header-navigation/header.tsx:110 |
| Page gutter pair on the app header | `{component.header-navigation}` | src/components/application/app-navigation/header-navigation.tsx:165 |
| Page gutter pair on a full-page layout | — | src/pages/not-found.tsx:10 |
| Section band rhythm | — | src/pages/not-found.tsx:9 |
| Container max width | `--max-width-container` | src/styles/theme.css:46 |
| Local width caps: headline blocks | — | src/pages/not-found.tsx:11, src/pages/home-screen.tsx:17 |
| Local width cap: empty state | — | src/components/application/empty-state/empty-state.tsx:23 |
| Local width cap: slideout | `{component.slideout-menu}` | src/components/application/slideout-menus/slideout-menu.tsx:37 |
| Local width cap: dropdown popover | `{component.dropdown-popover}` | src/components/base/dropdown/dropdown.tsx:146 |
| Sidebar width driven by a CSS variable | `{component.sidebar}` | src/components/application/app-navigation/sidebar-navigation/sidebar-simple.tsx:50 |
| Whitespace step-up pairing sites | — | src/pages/not-found.tsx:11-12; src/components/application/slideout-menus/slideout-menu.tsx:85,95,104 |
| Shadow ramp and skeuomorphic composites | `--shadow-*` | src/styles/theme.css:66-88 |
| Shadow tallies: xs ×40, sm ×22, md ×25, lg ×34, xl ×4, 2xl ×1, xs-skeuomorphic ×11, 3xl ×0 | `--shadow-*` | tally across src/components, src/pages |
| Mockup shadow composites and device drop shadow defined, never used | `--shadow-modern-mockup-*`, `--drop-shadow-iphone-mockup` | src/styles/theme.css:77-88 |
| Device mockup exists but applies no shadow | — | src/components/shared-assets/iphone-mockup.tsx |
| Masked white inner border on solid fills | `{component.button-primary}` | src/components/base/buttons/button.tsx:59 |
| Masked white inner border on dark featured icon | `{component.featured-icon-dark}` | src/components/foundations/featured-icon/featured-icon.tsx:48 |
| Seven-layer composite shadow, written inline | `modern-neue` theme | src/components/foundations/featured-icon/featured-icon.tsx:84 |
| Four background patterns at three sizes | — | src/components/shared-assets/background-patterns/index.tsx:8-13 |
| Grid pattern geometry, color and radial mask | — | src/components/shared-assets/background-patterns/grid.tsx:13-31 |
| Grid-check hard-codes two hexes, not theme-aware | — | src/components/shared-assets/background-patterns/grid-check.tsx:21-73 |
| Four line illustrations at three sizes | — | src/components/shared-assets/illustrations/index.tsx:7-12 |
| Avatar contrast border and masked inner border | `{component.avatar}` | src/components/base/avatar/avatar.tsx:147-151 |
| Radius scale, ten tokens | `{rounded.*}` | src/styles/theme.css:54-63 |
| Radius tallies: md ×31, xl ×15, 2xl ×5, default ×21, none ×3, xs ×1, sm ×0, 3xl ×0 | `{rounded.*}` | tally across src/components, src/pages |
| 7px inner-border partner on every button size | `{component.button-primary}` | src/components/base/buttons/button.tsx:24,32,39,45,49 |
| 7px as the avatar's squared fallback | `{component.avatar}` | src/components/base/avatar/avatar.tsx:135 |
| Dark featured-icon radius pairs | `{component.featured-icon-dark}` | src/components/foundations/featured-icon/featured-icon.tsx:50-53 |
| Modern-neue even-step radius ladder | `modern-neue` theme | src/components/foundations/featured-icon/featured-icon.tsx:87-90 |
| Icon library counts and PRO variants | — | CLAUDE.md:195-197 |
| Icon sizing convention, three steps | — | CLAUDE.md:218-219 |
| `size-5` as the shared button icon class | `{component.button-primary}` | src/components/base/buttons/button.tsx:19 |
| Stroke compensation at `size-4` | — | src/components/base/buttons/button.tsx:26; src/components/base/input/input.tsx:74; src/components/foundations/featured-icon/featured-icon.tsx:7 |
| Heavier navigation chevron strokes | `{component.nav-item}`, `{component.nav-menu-item}` | src/components/application/app-navigation/base-components/nav-item.tsx:68,79; src/components/marketing/header-navigation/header.tsx:58,131 |
| Two icon-passing conventions; data-icon required on elements | — | CLAUDE.md:205-212 |
| Brand asset inventory: 57 payment, 23 social, 17 integration, 2 wordmarks | — | src/components/foundations/ |
| Avatar images cover-fit across six sizes | `{component.avatar}` | src/components/base/avatar/avatar.tsx:146-152 |
| Component surface counts: 67 primitives, 30 composed, 104 foundational, 3 chrome, 15 decorative | — | src/components/ |
| Sort helper is a no-op for tooling; merge helper extends tailwind-merge | — | src/utils/cx.ts:18-24 |
| Marketing header heights, floating chrome, asymmetric gutter, wordmark swap | `{component.marketing-header}` | src/components/marketing/header-navigation/header.tsx:104-119 |
| Nav menu item type, radius, padding, chevron rotation | `{component.nav-menu-item}` | src/components/marketing/header-navigation/header.tsx:128-131 |
| App header rail and secondary row height | `{component.header-navigation}` | src/components/application/app-navigation/header-navigation.tsx:165-203 |
| Sidebar nav item geometry, states, label and icon roles, nested indent | `{component.nav-item}` | src/components/application/app-navigation/base-components/nav-item.tsx:8-90 |
| Five sidebar variants; fill, top and content padding | `{component.sidebar}` | src/components/application/app-navigation/sidebar-navigation/sidebar-simple.tsx:50-67 |
| Button defaults: size sm, color primary | `{component.button-primary}` | src/components/base/buttons/button.tsx:173-174 |
| Button size ladder: padding, type, icon-only padding, icon overrides | `{component.button-primary}` | src/components/base/buttons/button.tsx:22-52 |
| Nine color variants and their recipes | button family | src/components/base/buttons/button.tsx:54-128 |
| Loading spinner construction and sibling-hiding behaviour | `{component.button-primary}` | src/components/base/buttons/button.tsx:223-251 |
| Links are buttons with href, swapping the underlying element | `{component.button-link}` | src/components/base/buttons/button.tsx:186; CLAUDE.md:641 |
| Utility button sizes, colors, foreground, built-in tooltip | `{component.button-utility}` | src/components/base/buttons/button-utility.tsx:10-13 |
| Social button sizes and themes | `{component.social-button}` | src/components/base/buttons/social-button.tsx:15-41 |
| Social button references disabled tokens that do not exist | `{component.social-button}` | src/components/base/buttons/social-button.tsx:9 (absent from src/styles/theme.css) |
| Input wrapper fill, ring, shadow, transition; focus and invalid states | `{component.input}` | src/components/base/input/input.tsx:94-110 |
| Input size ladder and icon insets | `{component.input}` | src/components/base/input/input.tsx:70-88 |
| Textarea sizes; resize grip generated at runtime with two hard-coded hexes | `{component.textarea}` | src/components/base/textarea/textarea.tsx:9-37 |
| Label type, layout, required marker, group-driven error flip | `{component.label}` | src/components/base/input/label.tsx:26-37 |
| Hint text type and small-size step-down | `{component.hint-text}` | src/components/base/input/hint-text.tsx:20-28 |
| Checkbox sizes, radii, fill grammar, cross-faded marks | `{component.checkbox}` | src/components/base/checkbox/checkbox.tsx:17-52 |
| Radio sizes, fill grammar, inner dot | `{component.radio-button}` | src/components/base/radio-buttons/radio-buttons.tsx:28-37 |
| Toggle geometries, track fill, ring, hand-authored split transition | `{component.toggle}` | src/components/base/toggle/toggle.tsx:17-70 |
| Slider rail, fill, handle, cursor, value bubble | `{component.slider-handle}` | src/components/base/slider/slider.tsx:15-55 |
| Pin-input six-step ladder, placeholder opacity, caret | `{component.pin-input}` | src/components/base/input/pin-input.tsx:52-57,113 |
| File-upload drop zone, disabled fill, rows, status line roles | `{component.file-upload}` | src/components/application/file-upload/file-upload-base.tsx:202-290 |
| Select item padding ladder and icon steps | `{component.select-item}` | src/components/base/select/select-shared.tsx:39-46 |
| Table container, header, pseudo-element rules, cell type, hover, scroll | `{component.table}` | src/components/application/table/table.tsx:53-271 |
| Modal overlay, blur, anchoring, enter and exit curves, panel radius | `{component.modal}` | src/components/application/modals/modal.tsx:9-34 |
| Slideout width, shadow, overlay, leading inset, inset footer rule | `{component.slideout-menu}` | src/components/application/slideout-menus/slideout-menu.tsx:19-104 |
| Dropdown popover width, radius, shadow, ring, origin; item gutter; separator | `{component.dropdown-popover}` | src/components/base/dropdown/dropdown.tsx:83-161 |
| Tooltip radius, fill, padding, type, delays, offset, cross-offset, arrow | `{component.tooltip}` | src/components/base/tooltip/tooltip.tsx:50-90 |
| Empty-state composition, defaults, marquee timing, reduced-motion | empty state | src/components/application/empty-state/empty-state.tsx:23-306 |
| Section divider rail and rule | `{component.section-divider}` | src/components/shared-assets/section-divider.tsx:6-8 |
| Badge types, colors, radii, ring, shadow, size ladder, defaults | `{component.badge-pill}` | src/components/base/badges/badges.tsx:75-129 |
| Badge utility-ramp formula across twelve colors | `{component.badge-pill}` | src/components/base/badges/badges.tsx:8-68 |
| Modern badge add-on uses a raw palette class | `{component.badge-modern}` | src/components/base/badges/badges.tsx:87-90 |
| Tag three-size ladder with per-affordance padding compensation | `{component.tag}` | src/components/base/tags/tags.tsx:72-107 |
| Dot icon geometry and currentColor use | `{component.dot-icon}` | src/components/foundations/dot-icon.tsx:3-19 |
| Tab types, defaults, label type and icon steps | `{component.tab}` | src/components/application/tabs/tabs.tsx:50-69 |
| Tab selection treatments; hover and selected styled identically | `{component.tab-active}` | src/components/application/tabs/tabs.tsx:17-48 |
| Tab container chrome per type | `{component.tab}` | src/components/application/tabs/tabs.tsx:72-78 |
| Featured icon themes, colors, sizes, glyph steps | `{component.featured-icon-light}` | src/components/foundations/featured-icon/featured-icon.tsx:6-11 |
| Modern-neue color slots empty except gray | `modern-neue` theme | src/components/foundations/featured-icon/featured-icon.tsx:92-96 |
| Modern themes documented as gray-only | — | CLAUDE.md:635 |
| Avatar sizes, initials ramp, default rounding, border inset, sub-parts | `{component.avatar}` | src/components/base/avatar/avatar.tsx:69-152 |
| Progress bar track, fill, 75ms transition, value label | `{component.progress-bar}` | src/components/base/progress-indicators/progress-indicators.tsx:45-113 |
| Progress circle value type ladder | progress circles | src/components/base/progress-indicators/progress-circles.tsx:23-44 |
| Loading indicator types, sizes, label type, spinner construction | `{component.loading-indicator}` | src/components/application/loading-indicator/loading-indicator.tsx:3-60 |
| Pagination item geometry, type, hover, radius toggle, mobile summary | `{component.pagination-item}` | src/components/application/pagination/pagination.tsx:23-167 |
| Date cell geometry, range rounding, feathered gradient edges, states, event dots | `{component.date-cell}` | src/components/application/date-picker/cell.tsx:47-98 |
| Chart tooltip grammar, active dot, legend type | `{component.chart-tooltip}` | src/components/application/charts/charts-base.tsx:60-135 |
| Chart focus-outline reset | — | src/styles/globals.css:65-68 |
| Role-classes-only rule; named anti-pattern classes | — | CLAUDE.md:697-711, CLAUDE.md:703-705 |
| Re-brand adapts across modes through the variable chain | — | CLAUDE.md:164 |
| Complete 25–950 scale with contrast ratios requested | — | CLAUDE.md:147 |
| Aria prefix rationale, three reasons | — | CLAUDE.md:19-32 |
| Unprefixed import named as the anti-pattern | — | CLAUDE.md:24-25 |
| Kebab-case file naming rule | — | CLAUDE.md:36-58 |
| PascalCase and camelCase named as the anti-pattern | — | CLAUDE.md:45-49 |
| House transition described as snappy without being jarring | — | CLAUDE.md:259-267 |
| Disabled expressed as cursor plus opacity | — | CLAUDE.md:280-281 |
| Retired disabled token trio | — | CLAUDE.md:283-284 |
| Icon-passing conventions | — | CLAUDE.md:205-212, CLAUDE.md:688-691 |
| aria-hidden on decorative icons | — | CLAUDE.md:227-228 |
| Sort helper visible to the class sorter | — | src/utils/cx.ts:18-24; .prettierrc |
| Two custom breakpoints declared; Sonner-matching comment | `--breakpoint-xxs`, `--breakpoint-xs` | src/styles/theme.css:49-51 |
| Breakpoint hook mirrors the five inherited defaults | — | src/hooks/use-breakpoint.ts:3-9 |
| Breakpoint hook listener and SSR-safe default | — | src/hooks/use-breakpoint.ts:20-33 |
| Mobile nav panel: fill, shadow, hidden scrollbar, stacked items | `{component.marketing-header}` | src/components/marketing/header-navigation/header.tsx:122,192,219-227 |
| Mobile nav item rows and section wrapper | `{component.nav-menu-item}` | src/components/marketing/header-navigation/header.tsx:42,68 |
| Headline ramps up across three breakpoints | — | src/pages/not-found.tsx:15 |
| Prose ramp switch at the primary breakpoint | `.md:prose-lg` | src/styles/typography.css:275-281 |
| Button rows reverse on narrow screens | — | src/pages/not-found.tsx:20 |
| Avatar image fallback chain | `{component.avatar}` | src/components/base/avatar/avatar.tsx:146 |
| Prose image sizing | `.prose` | src/styles/typography.css:168-176 |
| Device mockup aspect-ratio handling and dark asset swap | — | src/components/shared-assets/iphone-mockup.tsx:28-40 |
| Dark block spans roughly 360 of 856 lines | `.dark-mode` | src/styles/theme.css:497-856 |
| Theme provider modes, storage key, system subscription and key removal | — | src/providers/theme-provider.tsx:41-77 |
| Anti-flash inline script | — | index.html:21-27 |
| Storage-key mismatch between script and provider | — | index.html:21-27 vs src/providers/theme-provider.tsx:37 |
| Dark block re-declares the property mirrors | — | src/styles/theme.css:759-855 |
| Two mirrors declared in dark only | `--background-color-border-tertiary`, `--text-color-white` | src/styles/theme.css:791, src/styles/theme.css:800 |
| White text color declared twice in the light block | `--color-text-white` | src/styles/theme.css:297, src/styles/theme.css:435 |
| Overlay enter and exit asymmetry | `{component.modal}` | src/components/application/modals/modal.tsx:15-16,29-30 |
| Transition-inheritance utility | — | src/styles/globals.css:25-29 |
| Marquee animation definition | `--animate-marquee` | src/styles/theme.css:91,94-102 |
| Caret-blink animation definition | `--animate-caret-blink` | src/styles/theme.css:92,104-112 |
| Motion library available for complex animation | — | package.json:17; CLAUDE.md:255-258 |
| Re-brand is a single-file edit | — | CLAUDE.md:142-164 |
| Theme-color meta tag must change by hand | `{colors.brand-600}` | index.html:8 |
| Property mirror layer re-exports roles unchanged | — | src/styles/theme.css:401-494 |
| Three plugins registered | — | src/styles/globals.css:5-7 |
| Three custom variants | — | src/styles/globals.css:9-11 |
| Two custom utilities | — | src/styles/globals.css:13-29 |
| Five global resets | — | src/styles/globals.css:42-68 |
| Style objects keyed common / sizes / colors | `{component.button-primary}` | src/components/base/buttons/button.tsx:8-129 |
| Placement by kind across five folders | — | CLAUDE.md:73-85 |
| Size and color ladders expected where applicable | — | CLAUDE.md:679 |
| Documentation drift: theme context module path | — | CLAUDE.md:317 vs src/providers/theme-provider.tsx |
| Documentation drift: brand-25 step | — | CLAUDE.md:147-161 |
| Documentation drift: subtle secondary background role | `bg-secondary_subtle` | CLAUDE.md:793 (absent from src/styles/theme.css) |
| Raw palette classes in the credit-card asset | — | src/components/shared-assets/credit-card/credit-card.tsx:30-187 |
| Raw palette classes in the empty-state gradient | — | src/components/application/empty-state/empty-state.tsx:54 |
| Raw palette class in the rating stars | — | src/components/foundations/rating-stars.tsx:30 |
| Larger component set exists beyond this surface | — | README.md:50-56 |
| Buttons named as the most frequently used element | `{component.button-primary}` | CLAUDE.md:350 |
