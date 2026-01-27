# Mother: Xenomorph Website Parser

Welcome to the **Xenomorph Website Parser**. This is a custom-built HTML/CSS parser and inspector designed specifically for the Faculty of Fine Arts of the University of Porto Communication Design bachelor students. It goes beyond the W3C validator by enforcing the specific "Progressive Enhancement" and "Mobile First" methodologies taught in class.

<img width="1287" height="878" alt="Screenshot 2026-01-27 at 01 59 58" src="https://github.com/user-attachments/assets/4cd0d1b2-3fb9-4946-afaf-662b10944950" />


## How it works

1. **Visual Analysis:** Before running the code check, perform your manual visual audit.
2. **URL Entry:** Paste the student's live site URL.
3. **Diagnostic:** The tool parses the DOM and CSSOM to check for:
   - **Hygiene:** Are files named correctly? Is the code indented?
   - **Semantics:** Is the landmark structure efficient?
   - **Responsive Logic:** Is it mobile-first? Are images using `srcset`?
   - **Accessibility:** Does the color contrast pass AA/AAA?

## Usage

1. Enter the URL of the student project.
2. Click **Inspect**.
3. Review the 3-column report to see the progression from Fundamental to Advanced mastery.

## Interpreting Results

- **Optimal:** Ready for production.
- **Minor Issues:** Needs some "cleaning" (Indentation or missing comments).
- **Major Issues:** Fundamental errors in structure or RWD approach.

## Why the Alien Pun?

Like the Weyland-Yutani "Mother" computer, this tool sees everything in the code. Don't let your code be a "chest-burster"—clean it up!

## Developed by

Pedro Amado (FBAUP / i2ADS / Ligatures) with Gemini 3 Pro. Version 0.1. January 2026. Available online https://github.com/pedamado/xenomorph. Website live at https://pedamado.github.io/xenomorph/

---

## 👾 Mother's Cheat-Sheet: Curricular Reference

### 1. HTML Foundations & Semantics

The skeletal structure must be clean, ASCII-compliant, and semantically mature.

| Category          | Elements / Attributes                                                          | Audit Logic                                                                  |
| :---------------- | :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------- |
| **Hygiene**       | Filenames, Index.html                                                          | [cite_start]Lowercase, no spaces, ASCII only. [cite: 1]                      |
| **Document**      | `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`                                | [cite_start]Standard HTML5 structure. [cite: 1]                              |
| **Meta**          | `charset="UTF-8"`, `viewport`, `description`, `title`                          | [cite_start]Mandatory SEO and RWD tags. [cite: 1]                            |
| **Landmarks**     | `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>` | [cite_start]Logical content mapping. [cite: 1, 2]                            |
| **Aria**          | `aria-label`, `aria-labelledby`                                                | [cite_start]Required for duplicate landmarks (e.g., dual Navs). [cite: 1]    |
| **Typography**    | `<h1>` through `<h6>`, `<p>`, `<ul>`, `<ol>`, `<li>`                           | [cite_start]Hierarchy: One H1 per page; structured lists. [cite: 1]          |
| **Inline**        | `<strong>`, `<em>`, `<blockquote>`, `<abbr>`, `<time>`, `<ins>`, `<del>`       | [cite_start]Semantic formatting over visual-only tags. [cite: 1]             |
| **Media**         | `<img>`, `<figure>`, `<figcaption>`, `<picture>`, `<source>`                   | [cite_start]`alt` text > 3 chars; responsive image logic. [cite: 2]          |
| **Embedded**      | `<video>`, `<audio>`, `<iframe>`                                               | [cite_start]Native media vs. external embeds (YouTube/Soundcloud). [cite: 2] |
| **Interactivity** | `<a>` (internal/relative/email), `target="_blank"`                             | [cite_start]Link types and window behavior. [cite: 1, 2]                     |
| **Form Logic**    | `<input>` (checkbox/radio), `popover`, `details`, `summary`                    | [cite_start]State-driven UI patterns (Pure CSS toggles). [cite: 2]           |

### 2. CSS Architecture & Box Model

We prioritize Progressive Enhancement, relative units, and the "Logic of the Box."

| Category          | Selectors / Properties                                                | Audit Logic                                                                  |
| :---------------- | :-------------------------------------------------------------------- | :--------------------------------------------------------------------------- |
| **Selectors**     | `*`, Tag, `.class`, `#id`, `Parent > Child`                           | [cite_start]Cascade management and specificity. [cite: 1, 2]                 |
| **Reset**         | `margin: 0`, `padding: 0`, `box-sizing: border-box`                   | [cite_start]Predictable box model initialization. [cite: 1, 2]               |
| **RWD Units**     | `%`, `em`, `rem`, `vw`, `vh`, `dvh` (fallbacks)                       | [cite_start]Avoid fixed pixels for layout/type. [cite: 1, 2]                 |
| **Typography**    | `font-family`, `font-size`, `line-height`, `font-stack`, `@font-face` | [cite_start]Systematic type scaling (Major Third/Golden Ratio). [cite: 1, 2] |
| **Color**         | `HEX`, `RGB`, `RGBA`, CSS Variables                                   | [cite_start]WCAG AA/AAA Contrast verification. [cite: 1]                     |
| **Positioning**   | `relative`, `absolute`, `fixed`, `sticky`, `z-index`, `isolation`     | [cite_start]Control flow; flag over-use of Absolute. [cite: 2]               |
| **Layout**        | `inline-block`, `flex`, `grid`, `aspect-ratio`                        | [cite_start]From basic flow to advanced grids. [cite: 2]                     |
| **Advanced RWD**  | `clamp()`, `min()`, `max()`, Media Queries                            | [cite_start]Mobile-first breakpoints (>600px). [cite: 2]                     |
| **The "New Age"** | `scroll-timeline`, `anchor-name`, `text-wrap: balance`, `:has()`      | [cite_start]Emerging/Future-proof CSS techniques. [cite: 2]                  |

### 3. Master Constraints (The Pedagogical "Rules")

- **The 4-Unit Rule:** Consistent sizing (margins, paddings, radius) should vary by no less than 4 units.
- **The Type Scale:** Minimum Body text of 16px/1em. Helper text no lower than 14pt.
- **The Mobile-First Rule:** Styles must start small; use `@media(min-width)` for growth.
- **The Inheritance Rule:** Classes should build upon inherited properties, not redefine them.
