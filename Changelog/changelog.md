# Changelog

All notable changes to the Fairway Finds web application project are documented in this file.


---

## [1.0.0] - 2026-08-28

### Added
- Initialized core repository folder architecture and file structure.
- Created global header navigation structure across all six primary HTML pages (`index.html`, `about.html`, `products.html`, `gallery.html`, `enquiry.html`, `contact.html`).

---

## [1.1.0] - 2026-08-29

### Added
- Developed `products.html` catalog featuring 3-column table layouts, product descriptions, pricing details, and direct enquiry links.

---

## [1.2.0] - 2026-08-30

### Added
- Built `gallery.html` photo grid layout with CSS hover transition effects.
- Implemented in-page category navigation jump anchors.

---

## [1.3.0] - 2026-08-31

### Added
- Developed `enquiry.html` form with `<optgroup>` selection fields for product inquiries.
- Added native HTML5 `<details>` and `<summary>` accordion widgets for store FAQ section.

---

## [1.4.0] - 2026-08-31

### Added
- Line-by-line descriptive HTML comments across all site template files.
- Finalized initial `README.md` documentation for Part 1 assessment submission.

---

## [2.0.0] - 2026-10-01

### Feedback Implementation & Corrections (Part 1 Review)
*This update directly addresses all comments provided in the Part 1 assessment feedback:*

- **Lecturer Comment 1: "A suggestion would be to remove the ul from the anchor elements."**
  - **Fixed:** Corrected navigation list syntax across all six HTML headers (`index.html`, `about.html`, `products.html`, `gallery.html`, `enquiry.html`, `contact.html`). Removed raw `<a>` tags nested directly inside `<ul>` elements and properly wrapped each link inside list item elements (`<ul><li><a href="...">Link</a></li></ul>`).

- **Lecturer Comment 2: "Your changelog should be in its own file outside of the readme."**
  - **Fixed:** Decoupled the project changelog from `README.md` into its own standalone `CHANGELOG.md` file located in the root repository directory. Added a direct reference link to `CHANGELOG.md` within `README.md`.

- **Lecturer Comment 3: "Commits could be more detailed, but it was insufficient for this part. Most of your commits was for the README and not the actual HTML."**
  - **Fixed & Detailed:** Re-architected version entries to comprehensively document granular HTML element updates, layout refactoring, form control CSS additions, and component-level code changes rather than high-level repository edits.

- **Lecturer Comment 4: "Using more references could have strengthened your work/Use more in-text citations where applicable."**
  - **Added:** Integrated formal academic and technical W3C/MDN web standard references alongside in-text citations across all project documentation and Part 1 implementation reports.

### Added
- **External CSS Form Controls:** Added `.form-group`, `.btn-submit`, `.btn-reset`, `input`, `select`, and `textarea` styling rules inside `css-assets/styles.css`.
- **Interactive FAQ Accordions:** Custom styled `<details>` and `<summary>` components on `enquiry.html`.
- **Responsive Map Embeds:** Added responsive wrapper rules for iframe Google Maps on `contact.html`.

### Changed
- **Form Layout Refactoring:** Replaced legacy table-based form grids in `contact.html` with modern, accessible semantic CSS form block containers.
- **Header CSS:** Updated `styles.css` with horizontal flexbox rules (`display: flex`, `list-style: none`, `gap: 8px`) to style the newly structured `<ul>` and `<li>` navigation items cleanly.

### Fixed
- **Deprecated HTML Tags:** Completely removed outdated presentational markup (`<font>`, `<center>`, `<br>`) and inline layout attributes (`align`, `border`, `cellpadding`, `width`) from `contact.html` and `enquiry.html` to enforce pure separation of concerns.

---

## [2.1.0] - 2026-10-04

### Added
- **Responsive Layout Media Queries:** Added `@media screen and (max-width: 768px)` media query rules to Section 14 of `styles.css` for tablet and mobile viewports.
- **Landscape & Short Viewport Support:** Implemented `@media screen and (max-height: 450px)` rules to rescale image containers and 3D flip card heights on mobile landscape screens.
- **Embedded Media Safeguards:** Added responsive wrapper rules forcing `iframe` elements to dynamic `max-width: 100%` width constraints.

### Changed
- **Product & Testimonial Grid Cards:** Refactored `table`, `tr`, `tbody`, and `td` layout rules under Section 9/14 to render as full-width block elements on screens $\le 768\text{px}$, preventing horizontal table distortion.
- **Header Navigation Flex Alignment:** Updated header navigation rules (`header nav ul`) to center-align and wrap cleanly on smaller viewports (`justify-content: center`, `gap: 8px 12px`).
- **Form Controls Mobile Stacking:** Configured secondary form reset buttons (`.btn-reset`) to wrap cleanly under submit controls on narrow viewports.