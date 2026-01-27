# Changelog

## **[1.9.3] - 2026-01-27**

### **Added**

- **Module: File I/O:** Renamed from File Naming; integrated "Pretty Code" indentation check.
- **Module: CSS Architecture:** Moved to primary position; identifies filenames and relative paths; flags internal/inline styles.
- **Module: Meta Info:** Dedicated audit for charset, viewport, description, author, title, favicon, and theme-color.
- **Module: CSS Selectors:** Implemented $XXX / YYY$ coverage ratio (ignoring meta tags) and landmark selector presence.
- **Module: Identity & Box Model:** Added checks for redundant IDs, ID/Class naming collisions, and positioning thresholds (absolute/fixed warning > 20%).
- **Module: Media Audit:** Basic alt vs Advanced srcset/figure/picture detection.
- **Mastery Expansion:** Exploration checklist now audits pseudo-classes, pseudo-elements, anchor types (rel/abs/mail), webfonts, variables, and HTML entities.

### **Fixed**

- **CSS Selectors:** Properly excludes administrative tags from the coverage ratio logic.

## **[1.9.1] - 2026-01-27**

### **Added**

- **Responsive UI Themes:** Light and Dark mode switching via prefers-color-scheme.
- **Alien Phrases:** Bank of 20 random CTAs and synthetic audit adendas.

## [1.6.0] - 2026-01-27

### Added

- **Exploration Heuristics**: New module to detect `clamp()`, `grid`, `flex`, and animations.
- **Semantic Tags**: Logic to flag the presence of `strong`, `em`, `small`, and `time`.
- **Top-N Listing**: RWD Logic now limits results to the first 5 optimal and 10 restricted units.

### Fixed

- **RWD Rebuild**: Corrected logic to allow fixed units in `min-`, `max-`, and `@media` while restricting them for component dimensions.
- **Documentation**: Synchronized all `.md` files.

## [0.1.0] - 2026-01-26

### Added

- Integrated `aria-label` identity check for duplicate landmarks.
- Added "Tidy Code" indentation audit.
- Implemented "Alt-Text Quality" check (>3 chars).
- Added HTML5 self-closing tag consistency (trailing slash check).
- Finalized FBAUP-specific vision and credit sections.
