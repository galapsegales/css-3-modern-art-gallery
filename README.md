# ✨ Modern Art Gallery — Responsive (Mobile-first)

[Visit on GitHub Pages](https://galapsegales.github.io/css-3-modern-art-gallery/)

> Mobile-first, responsive site with 2 views: **Home (index.html)** and **Location (location.html)**. A sample project that showcases a modern gallery layout and adaptive design.

![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-C6538C?style=for-the-badge&logo=sass&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

---

## 🎯 About this project

**Modern Art Gallery** is a mobile-first, responsive landing page built to present artwork and the gallery location.

- Designed for small screens first and scaled up for tablets and desktops.
- SCSS-based structure using **BEM** and reusable mixins.
- Built with **Vite** for fast development and easy deployment.

### ✨ Key features

- 📱 **Mobile-first responsive design** — layouts adapt from mobile to tablet and desktop
- ⚡ **Fast and lightweight** — optimized with Vite and good CSS practices
- 🎨 **Minimal, bold aesthetic** with strong typography and modular composition
- 🧩 **BEM + SCSS** — clear, maintainable styles and components
- 🧭 **Two views**: `index.html` (Home) and `location.html` (Location)

---

## 📱 Responsive approach

This project follows a **mobile-first** workflow using:

- Breakpoints.
- Breakpoint mixins for consistent media queries.
- Techniques: `flexbox`, `aspect-ratio` for images (via the `gallery-switcher` mixin), and fluid layouts that rearrange on larger screens.
- Responsive images handled via the `gallery-switcher` mixin to preserve proportions and performance.

> Tip: check `src/styles/layout/_hero.scss` and `src/styles/pages/_location.scss` for concrete examples of how elements adapt at different breakpoints.

---

## 🖼️ Pages (Views)

- `index.html` — **Home**: main hero with featured images, information sections, and CTAs.
- `location.html` — **Location**: map or location image, contact details, and a CTA to navigate back.

---

## 🧭 BEM structure

The project follows BEM for naming blocks, elements and modifiers. Real examples used in the code:

- Main blocks:
  - `.header` — header / navigation
  - `.hero` — main section (e.g. `hero__expo`, `hero__container`)
  - `.location` — location section (`.location--title`, `.location--subtitle`)
  - `.map` — map block (`.map__img`, `.map--cta`)
  - `.footer`, `.footerloc`, `.footer-maps` — footer and variations
  - `.btn`, `.btn-rev` — buttons (`.btn__arrow`, `.btn-rev__arrow`)
  - `.container` — layout container

- Convention: `.block`, `.block__element`, `.block--modifier`.

---

## 👤 Author

**Gala P Segalés** — [@galapsegales](https://github.com/galapsegales)
