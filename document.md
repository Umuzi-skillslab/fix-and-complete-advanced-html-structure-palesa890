# Advanced Media Production Website - Capstone Project

## Project Overview
This project involved refactoring a legacy codebase into a high-performance, semantic, and fully responsive Media Production website. The focus was on HTML5 accessibility, advanced CSS layouts (Flexbox/Grid), and interactive animations.

## 9-Criteria Implementation Summary

### 1. Semantic HTML & Metadata
- Replaced all generic `<div>` containers with `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.
- Added `<meta charset="UTF-8">` and `viewport` for mobile responsiveness.
- **Status:** Validated via W3C Service.

### 2. Media Integration
- **Video:** Two videos implemented with `controls`, `poster` attributes, and fallback text.
- **Audio:** Audio player added for studio samples.
- **Iframe:** Google Maps location embed included.
- **Figures:** All 6+ portfolio/client images use `<figure>` and `<figcaption>`.

### 3. Advanced Forms & Validation
- Implemented 7+ input types: `text`, `email`, `tel`, `date`, `radio`, `checkbox`, and `select`.
- All inputs have associated `<label>` elements for accessibility.
- Added `required`, `pattern`, and `min/max` validation attributes.

### 4. Flexbox Layouts
- **Navigation:** Header uses Flexbox for alignment and distribution.
- **Services:** The "What We Do" section uses `flex-wrap` for responsive stacking.

### 5. CSS Grid Layouts
- **Media Gallery:** Uses CSS Grid with `auto-fit` and `minmax` for a fluid, responsive layout.

### 6. Selectors & Pseudo-classes
- Used 5+ selector types: Element, Class, ID, Attribute, and Child (`>`).
- Implemented 5+ pseudo-classes: `:hover`, `:focus`, `:active`, `:nth-child`, and `:not`.

### 7. CSS Effects & Animations
- **Effects:** Text-shadows on Hero text and linear-gradient overlays.
- **Transforms:** `scale`, `rotate`, and `translate` used on gallery and buttons.
- **Animations:** `@keyframes slideIn` for page entry and a CSS loading spinner.

### 8. Cross-Browser & Debugging
- Tested in **Google Chrome** and **Mozilla Firefox**.
- HTML/CSS validated with 0 errors. Screenshots included in `/screenshots`.

### 9. Code Quality
- Consistent indentation used throughout.
- CSS is organized by section (Variables, Reset, Layout, Components).
- Meaningful comments explain complex CSS logic.

## How to Run
1. Clone the repository.
2. Open `index.html` in any modern web browser.