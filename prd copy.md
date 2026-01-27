PRD: XenoMorph Web Analyzer (Digital Mother)

1. Vision & Goal

A specialized, static web application designed for the Webdesign Curricular Unit (FBAUP). It audits student projects against pedagogical benchmarks: Mobile-first discipline, Tidy Code, Semantic Maturity, Color Accessibility (WCAG), and Atomic Design patterns.

2. Technical Stack

Frontend: HTML5, CSS3 (JetBrains Mono Aesthetic), Vanilla JavaScript.

Engine: DOMParser + custom character-stream CSS parser.

3. High-Priority Modules (The 72-Point Logic)

Hygiene (1-12): ASCII naming, indentation, comments, external CSS only.

Structure (13-23): Universal reset, landmark hierarchy, relative units (%, rem, em).

Typography (16-17, 43): Type scales (1.25 ratio), min 16px body, clamp() usage.

Accessibility (18-22, 33): WCAG AA/AAA Contrast, Alt-text quality, aria-label.

Media (33, 67): Responsive <picture>, srcset, and object-fit: cover.

Advanced CSS (40-72): Grid/Flexbox, transitions/animations, CSS Variables, :has()/:is() selectors, and scroll-driven effects.

4. Scoring Framework

Optimal (Green): Fundamental requirements met; < 5% restricted units.

Minor (Yellow): 5-20% restricted units; missing non-critical semantic tags or comments.

Major (Red): > 20% restricted units; broken hierarchy; missing core landmarks.

2. Core Diagnostic Modules

File I/O: ASCII naming and "Pretty Code" indentation check.

CSS Architecture: External link verification and relative path identification.

Meta Info: Search/Social/Theme identity audit.

HTML5 Landmarks: Hierarchy breadcrumbs and landmark completeness.

CSS Selectors: Universal reset detection and HTML-to-CSS coverage ratio.

Identity & Box Model: ID/Class uniqueness, redundancy flagging, and positioning thresholds.

Typographic Hierarchy: Scale audit (p, a, ul, h1-h3) with 20%/4pt jump detection.

Color Contrast: Recursive WCAG checks for zones (nav a, main a, ul a, main p, main h1).

RWD Unit Logic: 2026 standards (Safe vs. Restricted units) with limited issue samples.

Exploration & Mastery: Mastery checklist (Pseudostates, Variables, Entities, Webfonts, Anchor Types).

3. Personality & UX

Theme: Alien/Weyland-Yutani terminal aesthetic.

Responsiveness: Automatic Light/Dark mode via prefers-color-scheme.

Feedback: Random cryptic messages from synthetics (Ash, Bishop, David) and ship computers (MU/TH/UR).

5. Credits

Developed by Pedro Amado (FBAUP / i2ADS / Ligatures) with Gemini 3 Pro. Version 0.5.
