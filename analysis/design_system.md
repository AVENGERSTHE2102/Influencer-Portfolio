# Design System Analysis

## 1. Color Palette
Extracted from `style.css`:

| Color | Hex/RGB | Usage |
|-------|---------|-------|
| **Primary Red** | `#FF0000` | Scrollbar thumb, potential accents |
| **Off White** | `#fafafa` | Scrollbar thumb (alternate), Backgrounds |
| **Line White** | `#fbfbfb` | Animation lines |
| **Grey** | `rgb(114, 114, 114)` | Background overlays, transform elements |

## 2. Typography
Fonts identified in the project (served via Typekit/Adobe Fonts):

### Headings / Display
- **Sharktooth** (`sharktooth`, `tk-sharktooth-n4/n7`) - Likely used for "Shaukia" logo texts.
- **Cubano** (`cubano`, `cubano-sharp`, `tk-cubano-*`) - Heavy display font for "PORTFOLIO", "CONTACT".
- **Rig Solid** (`rig-solid-*`) - 3D/Solid display effects.

### Body / UI
- **Aktiv Grotesk** (`aktiv-grotesk`, `tk-aktiv-grotesk-*`) - Main sans-serif text.
- **Base Mono Narrow** (`base-mono-narrow`) - Technical/Meta text.
- **Helvetica** - Used as valid fallback.

### Other
- **Baskerville Display PT** (`baskerville-display-pt`) - Serif accents.
- **Bee** (`bee`)
- **Marvin** (`marvin`, `marvin-round`, `marvin-shadow`)

## 3. Responsive Breakpoints
Based on `style.css` and `index.html` classes:
- **Mobile**: Default styles.
- **Desktop**: `@media (min-width: 992px)` - Interaction triggers and layout shifts.
- **Large Screen**: `@media screen and (min-width: 1600px)` - Scaling up typography and spacing.
