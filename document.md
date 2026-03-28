# Professional Media Production Website - Capstone Project

## 1. Project Overview
This website is a professional digital storefront for a Media Production Company. Its purpose is to showcase high-fidelity video and audio portfolios, provide service information, and capture client leads through an advanced, accessible contact system. 

## 2. Issues Found in Starter Code
The original codebase contained over 25 critical errors:
- **Structural:** Reliance on `<div>` tags with no semantic meaning.
- **Accessibility:** Missing `<label>` tags and `alt` attributes for images.
- **Technical:** Missing metadata (viewport, description) and broken video/audio elements.
- **Styling:** No responsive design, no Flexbox/Grid, and no interactive visual feedback.

## 3. Fixes and Implementations
I refactored the entire project to meet HTML5 standards:
- **Semantic Overhaul:** Implemented `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
- **Media Fixes:** Added `controls` to video/audio and used `<figure>`/`<figcaption>` for 6+ images.
- **Form Upgrade:** Created a two-part form with 7+ input types and group-level `<fieldset>` tags.

## 4. Advanced Layouts
- **Flexbox (2+ Layouts):** - **Navigation:** Uses `justify-content: space-between` to separate the branding from links.
  - **Services:** Uses `flex-wrap: wrap` and `justify-content: space-around` to ensure service cards stack beautifully on mobile.
- **CSS Grid:** - **Portfolio/Testimonials:** Implemented a responsive grid using `repeat(auto-fit, minmax(300px, 1fr))`, allowing the layout to rearrange itself without manual media queries for every screen size.

## 5. Selectors & Pseudo-classes
- **Selectors used:** Element (`body`), Class (`.nav`), ID (`#contact`), Attribute (`a[href]`), and Child (`.container > p`).
- **Pseudo-classes:** `:hover` (navigation), `:focus` (form inputs), `:active` (button click), `:nth-child` (zebra-striping testimonials), and `:not` (styling non-active links).

## 6. Animations, Effects, & Transforms
- **Transforms:** Applied `scale(1.1)` on hover, `rotate(2deg)` on images, and `translateY(2px)` for button feedback.
- **Transitions:** Smooth `0.3s` eases on all interactive states (color, shadows, transforms).
- **Animations:** A multi-step `@keyframes slideIn` for the Hero text and a 3-dot `pulse-wave` loading animation using staggered delays.
- **Text Effects:** Integrated `text-shadow` for readability and `linear-gradient` overlays on the hero background.

## 7. Accessibility & Compatibility
- **Accessibility:** Added ARIA roles, ensured 100% label-to-input associations, and maintained high color contrast.
- **Cross-Browser:** Tested on **Chrome** and **Firefox**. Used `standard-box-sizing` and generic font-families to ensure consistent rendering.
- **W3C Validation:** Both HTML and CSS files pass with zero errors.

## 8. How to View Locally
1. Clone this repository.
2. Ensure the file structure matches the `/css`, `/images`, and `/media` folders.
3. Open `index.html` in any modern browser (Chrome recommended).

## 9. Reflection & Challenges
The greatest challenge was implementing the **CSS Grid** for the testimonial section while maintaining image aspect ratios. I solved this by using `object-fit: cover` on images within the grid items. Another challenge was the Git Permission 403 error, which I resolved by correctly re-routing my local origin to my personal fork rather than the organization's main repo.

## 10. Project Screenshots

| Feature | Screenshot Link |
| :--- | :--- |
| **Desktop View** | `screenshots/homepage-desktop.png` |
| **Mobile View** | `screenshots/homepage-mobile.png` |
| **Form Validation** | `screenshots/form-validation.png` |
| **Grid & Media** | `screenshots/grid-layout.png` |
| **Browser Comparison** | `screenshots/browser-check.png` |