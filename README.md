# Fairway Finds – E-Commerce Website

## 1. Project Title
**Fairway Finds Boutique E-Commerce Website**

---

## 2. Student Information
* **Student Name:** Ethan Naidoo
* **Student ID / Number:** ST10514423
* **Module Code:** Web Development 
* **Institution:** The Independent Institute of Education (IIE)
* **Academic Year:** 2026

---

## 3. Project Overview
Fairway Finds is a boutique e-commerce web platform designed for South African golf and padel sports enthusiasts. The website showcases high-performance apparel, padel rackets, bags, and match accessories. It utilizes pure HTML5 semantic layouts, clean tables for product alignment, interactive FAQ accordions, and specialized product enquiry forms to create a seamless browsing experience.

---

## 4. Website Goals and Objectives
* **Goal 1:** Provide a structured multi-page web platform showcasing boutique golf and padel equipment.
* **Goal 2:** Ensure clear visual alignment of product cards and media using clean, responsive CSS card layouts and external stylesheets.
* **Goal 3:** Enable direct customer communication through structured product enquiry forms with category selection and preferred contact methods.
* **Goal 4:** Deliver accessible, interactive customer support through pure HTML collapsible FAQ elements (`<details>` and `<summary>`).
* **Goal 5:** Ensure full cross-device accessibility through responsive media queries, scalable typography, and adaptable flexbox navigation.

---

## 5. Key Features and Functionality
* **Global Responsive Navigation:** Header menu providing links across all six pages (`index.html`, `about.html`, `products.html`, `gallery.html`, `enquiry.html`, `contact.html`) with flexible wrapping for mobile and desktop screens.
* **Product Catalog Grids:** Itemized display of products categorized into Golf Apparel, Padel Rackets, and Accessories with prices, detailed specifications, and enquiry triggers.
* **Interactive Media Gallery:** Dedicated lookbook/showcase with in-page anchor navigation (`#apparel`, `#rackets`, `#accessories`) and photo metadata.
* **Product Enquiry Form:** Complete submission interface with text inputs, radio buttons, grouped dropdown options (`<optgroup>`), and styled form controls.
* **Interactive FAQ Accordion:** Native collapsible Q&A section providing answers regarding delivery times, padel racket shapes, and return policies.
* **Responsive Layouts:** Mobile and tablet media queries (`@media screen and (max-width: 768px)`) ensuring smooth vertical stacking on small viewports.

---

## 6. Lecturer Feedback Implementation (Part 1 Review)
This Part 2 release directly addresses and implements all assessment feedback provided by the lecturer from Part 1:

1. **Header List Syntax Optimization:** Corrected navigation list syntax across all six HTML headers by removing raw `<a>` elements directly inside `<ul>` containers and properly wrapping them inside `<li>` list items (`<ul><li><a href="...">Link</a></li></ul>`).
2. **Standalone Changelog Decoupling:** Separated the project change log into its own standalone `CHANGELOG.md` file in the root directory while maintaining a reference summary within this documentation.
3. **Comprehensive Changelog Detail:** Refactored changelog entries to meticulously record granular HTML element updates, CSS selector additions, responsive layout tweaks, and file structure changes.
4. **Enhanced Academic & Standards References:** Strengthened documentation with formal IIE Harvard / Anglia Ruskin citations referencing W3C standards, MDN web documentation, and foundational web development literature.

---

## 7. Development Status & Part Submissions
* **Part 1 Scope:** Delivery of full semantic HTML5 page structure, text content, table layouts, descriptive inline comments, functional cross-page navigation, and local image path linkages.
* **Part 2 Scope:** Full external CSS stylesheet implementation (`styles.css`), responsive grid layout refactoring, interactive pseudo-classes (`:hover`, `:focus`), mobile/tablet media queries, implementation of Part 1 lecturer feedback, and decoupling of `CHANGELOG.md`.

---

## 8. Development Changelog Summary
*For the complete detailed commit log and itemized code changes, please refer to the main [`CHANGELOG.md`](./CHANGELOG.md) file.*

* **Version 2.1.0 (2026-10-04):** Added tablet/mobile media queries (`max-width: 768px`) and mobile landscape safeguards (`max-height: 450px`) in `css-assets/styles.css`; converted table grids into responsive block elements.
* **Version 2.0.0 (2026-10-01):** Implemented lecturer feedback (fixed header `<ul>` nesting, created standalone `CHANGELOG.md`, enhanced citations), removed deprecated presentational HTML attributes, and added external form control styling.
* **Version 1.4.0 (2026-08-31):** Added line-by-line descriptive HTML comments across all site template files and finalized Part 1 `README.md`.
* **Version 1.3.0 (2026-08-31):** Built `enquiry.html` form with `<optgroup>` product categories and interactive FAQ accordions.
* **Version 1.2.0 (2026-08-30):** Built `gallery.html` photo grid layout and implemented in-page jump anchor navigation.
* **Version 1.1.0 (2026-08-29):** Developed `products.html` catalog featuring 3-column layouts, item descriptions, and pricing details.
* **Version 1.0.0 (2026-08-28):** Initialized project directory structure and created global header navigation across all six HTML pages.

---

## 9. Screenshots (Responsiveness)
<img width="1201" height="658" alt="image" src="https://github.com/user-attachments/assets/720eda37-8644-4b3e-9f94-8715020d7740" />
<img width="944" height="664" alt="image" src="https://github.com/user-attachments/assets/e70db5c9-89eb-4389-9841-10cae6fd7dd0" />
<img width="863" height="717" alt="image" src="https://github.com/user-attachments/assets/cbb58707-583b-4ab1-bf21-bb2349ae516e" />
<img width="1704" height="940" alt="image" src="https://github.com/user-attachments/assets/eff8d103-f51a-4199-9632-1530305f84ff" />
<img width="942" height="704" alt="image" src="https://github.com/user-attachments/assets/f8a352c8-ed82-47d6-b7a2-1bf85ed6687e" />
<img width="1759" height="936" alt="image" src="https://github.com/user-attachments/assets/f0043901-1806-4354-b9b7-7bb295f78515" />

---

## 10. References
* Duckett, J. (2011) *HTML and CSS: Design and Build Websites*. Indianapolis: John Wiley & Sons.
* Gemini (2026) *AI assistant response to HTML5 website structure, academic rubric alignment, and feature conceptualization queries*, 31 August. Available at: <https://gemini.google.com> (Accessed: 31 August 2026).
* Keep a Changelog (2023) *How to maintain a readable changelog*, Keep a Changelog [online]. Available at: <https://keepachangelog.com/en/1.0.0/> (Accessed: 4 October 2026).
* Mozilla Developer Network (2026) *CSS: Cascading Style Sheets*, MDN Web Docs [online]. Available at: <https://developer.mozilla.org/en-US/docs/Web/CSS> (Accessed: 4 October 2026).
* Mozilla Developer Network (2026) *HTML: HyperText Markup Language*, MDN Web Docs [online]. Available at: <https://developer.mozilla.org/en-US/docs/Web/HTML> (Accessed: 31 August 2026).
* W3C (2023) *HTML5 Specification: A Vocabulary and Associated APIs for HTML and XHTML*, World Wide Web Consortium [online]. Available at: <https://www.w3.org/TR/html52/> (Accessed: 31 August 2026).
* W3C (2024) *CSS Responsive Web Design Modules*, World Wide Web Consortium [online]. Available at: <https://www.w3.org/TR/css-device-adapt-1/> (Accessed: 4 October 2026).
* W3Schools (2026) *CSS Responsive Web Design*, W3Schools Online Web Tutorials [online]. Available at: <https://www.w3schools.com/css/css_rwd_intro.asp> (Accessed: 4 October 2026).
* W3Schools (2026) *HTML Tag Reference*, W3Schools Online Web Tutorials [online]. Available at: <https://www.w3schools.com/tags/default.asp> (Accessed: 31 August 2026).

---

## 11. Repository Structure & Sitemap
```text
fairway-finds/
│
├── index.html         # Home page (Brand introduction and hero highlights)
├── about.html         # About Us page (Company history, mission, and core values)
├── products.html      # Products page (3x3 grid catalog across apparel, rackets, and accessories)
├── gallery.html       # Gallery page (Media photo showcase with section jump links)
├── enquiry.html       # Enquiry page (Product selection form and interactive FAQ accordion)
├── contact.html       # Contact page (Store address, operating hours, and contact info)
├── CHANGELOG.md       # Full detailed project revision history and version tracking
├── README.md          # Project documentation and rubric alignment report
│
├── css-assets/        # External stylesheet directory
│   └── styles.css     # Global master stylesheet (Desktop & Responsive Media Queries)
│
└── images/            # Local media assets directory
    ├── polo.jpg
    ├── trousers.jpg
    ├── jacket.jpg
    ├── racket-pro.jpg
    ├── racket-power.jpg
    ├── racket-bag.jpg
    ├── glove.jpg
    ├── padel-balls.jpg
    └── cap.jpg
