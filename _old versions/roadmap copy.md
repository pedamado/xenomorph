# Roadmap: Project Mother

### Phase 1: The Core Parser (Current Phase)

- [ ] Build the URL fetcher with CORS handling.
- [ ] Implement the `DOMParser` to extract landmarks and meta-data.
- [ ] Set up the 3-column reporting grid.

### Phase 2: Hygiene & Structure (Ex2 Focus)

- [ ] Implement ASCII regex for filenames.
- [ ] Add check for mandatory head tags (Viewport/Description).
- [ ] Landmark counter: Flag duplicate `<nav>` or `<aside>` without `aria-label`.

### Phase 3: Atomic Analysis & Design Systems (NEW)

- [ ] **Atomic Design Auditor:** Detect the hierarchy of Atoms (tags), Molecules (component groups), and Organisms (sections).
- [ ] Check for modular CSS reuse across `article` or `card` components.
- [ ] Logic: Identify if a "Molecule" (e.g., a figure with caption) is reused within different "Organisms."

### Phase 4: Advanced CSS Components (NEW)

- [ ] **Interactive Component Detector:** Flag the presence of Pure CSS Modals, Toasts, and Carousels.
- [ ] Verify the use of `:checked` states or `popover` attributes for these interactions.

### Phase 5: Visual Logic & Media (Ex3 Focus)

- [ ] CSS Selector Auditor: Check for landmark-specific selectors.
- [ ] Image Inspector: Audit `alt` text quality and detect `<picture>` or `srcset` usage.
- [ ] Positioning Auditor: Warn if `absolute` is used excessively (>20%).

### Phase 6: Final Diagnostics & RWD

- [ ] Color Contrast checker implementation.
- [ ] Tidy Code check (identifying unformatted or un-indented blocks).
- [ ] Media Query directionality check (Mobile-first verification).
