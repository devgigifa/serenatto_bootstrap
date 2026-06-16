# Serenatto Café & Bistrô

A responsive landing page for a fictional café, built as a Bootstrap 5 practice project. Covers a wide range of Bootstrap components in a realistic, content-rich single-page layout.

---

## Overview

Serenatto is a single-page site for a café and bistro, featuring sections for services, products, and a contact form. The page includes a dark mode toggle and is fully responsive across desktop, tablet, and mobile.

---

## Sections

- **Navbar** — fixed top, collapses into an offcanvas drawer on mobile
- **Hero banners** — three full-viewport parallax image sections
- **Services** — three cards (Café & Bistro, Buffet, Delivery), each opening a detailed offcanvas panel with an accordion
- **Products** — six product cards in a responsive grid, two with modal popups
- **Contact form** — floating labels, select, range slider, checkbox, and submit button
- **Footer** — social media links via Bootstrap Icons

---

## Bootstrap Components Used

| Component | Usage |
|---|---|
| Navbar + Offcanvas | Responsive navigation with mobile drawer |
| Cards | Services and product display |
| Offcanvas (×3) | Service detail panels |
| Accordion | Content inside each offcanvas |
| Modal (×2) | Product detail popups |
| Form controls | Floating labels, select, range, checkbox |
| Grid system | Responsive product layout |
| Utility classes | Spacing, typography, flex, colors |

---

## Tech Stack

- HTML5
- CSS3 (custom properties for brand colors)
- Bootstrap 5.3
- Bootstrap Icons 1.10
- JavaScript (dark mode toggle via `data-bs-theme`)

---

## Features

- **Dark mode** — toggle in the navbar switches between light and dark themes using Bootstrap's built-in theming
- **Fully responsive** — navbar collapses, grid reflows, cards stack on smaller screens
- **Parallax banners** — full-height sections with `background-attachment: fixed`

---

## Project Structure

```
serenatto/
├── assets/              # Images and favicon
├── index.html
├── style.css
├── script.js            # Dark mode toggle
└── README.md
```

---
