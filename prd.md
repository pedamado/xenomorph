# PRD: Mother (Xenomorph Website Parser)

## 1. Vision & Goal

A specialized, static web application designed for the Webdesign Curricular Unit of the Bachelor of Graphic and Communication Design of Faculty of Fine Arts of the University of Porto. It audits student-submitted URLs against specific pedagogical benchmarks: Mobile-first discipline, Tidy Code (ASCII naming), Semantic Maturity, Color Accessibility (WCAG), and Advanced RWD (Responsive Web Design) patterns.

## 2. Technical Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript.
- **Core Engine:** DOM Parser (to analyze HTML structure) and CSS Object Model (CSSOM) parser.

## **3. Core Diagnostic Modules**

1.  **File I/O:** ASCII naming and "Pretty Code" indentation check.
2.  **CSS Architecture:** External link verification and relative path identification.
3.  **Meta Info:** Search/Social/Theme identity audit.
4.  **HTML5 Landmarks:** Hierarchy breadcrumbs and landmark completeness.
5.  **CSS Selectors:** Universal reset detection and HTML-to-CSS coverage ratio.
6.  **Identity & Box Model:** ID/Class uniqueness, redundancy flagging, and positioning thresholds.
7.  **Typographic Hierarchy:** Scale audit (p, a, ul, h1-h3) with 20%/4pt jump detection.
8.  **Color Contrast:** Recursive WCAG checks for zones (nav a, main a, ul a, main p, main h1).
9.  **RWD Unit Logic:** 2026 standards (Safe vs. Restricted units) with limited issue samples.
10. **Exploration & Mastery:** Mastery checklist (Pseudostates, Variables, Entities, Webfonts, Anchor Types).

## 4. UI/UX Requirements (Alien-Themed)

- **Title (h1):** Mother (Xenomorph Website Parser)
- **Tagline (h2):** Diagnostic tool for surviving the web-development evolution in an age of AI.
- **Input:** Single text input for URL/URI + "Run Diagnostic" (Inspect) button.
- **Report Layout:** - **Header:** Basic Level Status (Optimal <5% issues; Minor <20%; Major >21%).
  - **Recommendations Section:** Visual summaries of structural, semantic, and CSS logic.
  - **The Grid:** Three-column vertical layout:
    1. Feature/Requirement Name.
    2. Fundamental/Basic Status (Assignment 1 focus).
    3. Optional/Advanced Status (Assignment 2 focus).

- - **Theme:** Alien/Weyland-Yutani terminal aesthetic.
- - **Responsiveness:** Automatic Light/Dark mode via prefers-color-scheme.
- - **Feedback:** Random cryptic messages from synthetics (Ash, Bishop, David) and ship computers (MU/TH/UR).

## 5. Requirement Checklist (The Logic Engine)

The app must cross-check 70+ features, categorized into:

- **Hygiene:** ASCII naming, Tidy Code (indentation), Comment usage.
- **HTML Structure:** Landmarks (Header, Nav, Main, Section, Footer, Aside), mandatory Meta tags (Viewport, Title, Description).
- **Semantic Content:** H1/H2 hierarchy, lists (UL/OL/LI), links (relative, absolute, email), and advanced tags (strong, em, blockquote, abbr, time, br, hr, entities).
- **CSS Logic:** External link only, Universal Selector reset, Landmark selectors, Box Model (Position/Display/Size), Relative units (%, EM, VW, VH), Type scale consistency (min 16pt/1em).
- **Advanced CSS:** Pseudo-classes (LVHA), Box Sizing, Parenting hierarchy, IDs/Classes uniqueness and semantics.
- **Media:** Responsive images (Img vs Picture/Figure), SourceSets, aspect-ratio awareness.
- **Modern Standards:** CSS Variables, `prefers-color-scheme`, Dynamic Viewport units (`dvh`) with fallbacks.
- **RWD:** Mobile-first verification (Media queries for >600px, not <600px).

## 5. Credits

Include a footer with the proper text credits and app version: "Developed by Pedro Amado (FBAUP / i2ADS / Ligatures) with Gemini 3 Pro. Version 1.9.3. January 2026. Available online https://github.com/pedamado/xenomorph. Website live at https://pedamado.github.io/xenomorph/"
