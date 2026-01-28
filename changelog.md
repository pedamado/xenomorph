# Changelog

- **Gemini 3 Pro AI changelog:** Somehow Gemini decides to purge some of the changelog versions/updates (and I forget to save them while iterating the builds)

## **[1.9.40] - 2026-01-27**

### **Fixed**

- **Multi-File Aggregation:** Overhauled CSS processing to aggregate all local/relative .css files into a single "Design Buffer" for auditing.
- **Strict Filtering:** Both CSS Selectors and Mastery modules now ignore reset.css, fonts.css, and any external absolute URLs (CDNs) to prevent interference with diagnostic accuracy.
- **Typographic Scale:** Fixed a syntax error in the tag label rendering (added missing parentheses to .toUpperCase()).

### **Added**

- **Stability Lock:** Preserved Shadow DOM isolation for Typography measurements.
- **Stability Lock:** Preserved Mobile-First vs. Desktop-First strategy analysis in the RWD module.
- **Maintenance:** Updated footer and internal versioning to v1.9.40.

## **[1.9.27] - 2026-01-27**

### **Fixed**

- **Module: CSS Selectors:** Implemented a strict origin filter. The auditor now ignores reset.css, fonts.css, and absolute external CSS links (webfonts/CDNs) to ensure metrics reflect student-authored design code.
- **Module: RWD Unit Logic:** Unified the boilerplate filter to ignore reset and font files in responsive unit calculations.
- **Diagnostic Accuracy:** Prioritizes analysis of style.css and styles.css whenever multiple local files are present.

## **[1.9.26] - 2026-01-27**

### **Added**

- **Module: RWD Unit Logic:** Implemented boilerplate filtering. Rules originating from reset.css are now ignored in unit audits to ensure the diagnostic reflects the student's intentional responsive choices.
- **Maintenance:** Updated footer and internal versioning to v1.9.26.

## **[1.9.25] - 2026-01-27**

### **Added**

- **Module: Identity & Box Model:** Expanded positioning feedback. The auditor now extracts and displays up to 2 real-world examples for each positioning type (Relative, Absolute, Fixed, and Sticky) detected in the code.
- **Maintenance:** Updated footer and internal versioning to v1.9.25.

## **[1.9.24] - 2026-01-27**

### **Added**

- **Color Contrast Enhancements:** Implemented WCAG 2.1 level feedback (AA/AAA pass/fail status).

## **[1.9.17] - 2026-01-27**

### **Fixed**

- **UI Restoration:** Brought back all missing examples, counts, and visual samples in the diagnostic table.
- **Chromatic Auditor:** Fixed detection of text over container backgrounds and CSS Variable resolution. Restored color swatches and samples.
- **Module Parity:** Re-aligned all modules to present the "First 5 Compliant" and "First 5 Failing" examples rule.

### **Added**

- **Visual Feedback:** Re-implemented the <del> and grey-out visual system for missing Landmarks, Meta tags, and Mastery skills.
- **Quantitative Summary:** XX / YY (ZZ%) counts restored to the Basic and Advanced summary cards.

## **[1.9.16] - 2026-01-27**

### **Changed**

- **Personality Purge:** Removed all references to Albert Kapr. Refocused on Alien/Weyland-Yutani cinematic themes.

## **[1.9.10] - 2026-01-27**

### **Added**

- **UI Logic:** Implemented `position: sticky` for the `.input-organism` command interface. The "Umbilical Link" now remains fixed at the top of the viewport during deep diagnostic scrolls.
- **UI Logic:** Added specific `z-index` layering and background persistence to the input area to prevent content overlap during navigation.

### **Fixed**

- **UX Stability:** Verified that recursive CSS variable resolution for both the Chromatic Auditor and Typographic Scale remains active and robust across all inspection modes.

## **[1.9.9] - 2026-01-27**

### **Fixed**

- **Chromatic Auditor:** Implemented a recursive CSS Variable resolver. Mother can now "see" through `var()` declarations to audit the true color contrast of elements using custom property palettes.
- **Typographic Audit:** Updated font-size detection to also resolve CSS variables if used for hierarchy scaling.

## **[1.9.8] - 2026-01-27**

### **Added**

- **UI Logic:** "Waiting for data input..." is now visible initially.
- **UI Logic:** The status message now blinks during active "Signal Lock" and disappears once the diagnostic report is generated.

## **[1.9.7] - 2026-01-27**

### **Changed**

- **UI UX:** Diagnostic summary area is hidden during the scan to focus the terminal on synthetic adendas.

## **[1.9.6] - 2026-01-27**

### **Fixed**

- **Chromatic Auditor:** Improved shorthand detection. The engine now correctly parses the `background` property (in addition to `background-color`) to extract palettes from complex declarations and named colors (e.g., `darkcyan`).
- **Identity Module:** Added explicit checks for IDs and Classes on main structural blocks (`header`, `nav`, `main`, `section`, `footer`).
- **Data Persistence:** Fixed a bug where manual overrides sometimes failed to trigger the full diagnostic suite.

### **Added**

- **Anatomical Summary:** Diagnostic messages now include references to skeletal junctions and typographic anatomy, inspired by Albert Kapr’s pedagogical approach to structure.

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
