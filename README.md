<div align="center">
<img width="1280" height="800" alt="Veloura banner" src="https://github.com/user-attachments/assets/ae3ff862-eb1c-4c92-996c-60a6eab084e2" />


<h1>Veloura — Luxury Jewellery Landing Page</h1>

<p>A fully responsive jewellery landing page built with React, Vite, and Tailwind CSS. Designed for a premium jewellery brand with a complete shopping experience including cart, wishlist, quick view, and smooth animations.</p>

<br/>

<img src="https://skillicons.dev/icons?i=react,vite,tailwind,js,css" alt="React, Vite, Tailwind CSS, JavaScript, CSS3" />

<br/>
<br/>

![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg?style=flat-square)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-AD8440?style=for-the-badge&logo=netlify&logoColor=white)](https://idyllic-sfogliatella-cf2330.netlify.app)
[![GitHub Repo](https://img.shields.io/badge/Repository-View%20Code-17120D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NSniha/jewellery-landing-page)

</div>

---

## What is Veloura?

**Veloura** is a luxury jewellery landing page built as a frontend portfolio project. It replicates a real-world jewellery brand website with professional UI, interactive shopping features, and a polished design system using gold accent colors, serif typography, and smooth animations.

This jewellery landing page is ideal as a reference project for anyone building a jewellery store website, ecommerce UI, or luxury brand landing page with React and Tailwind CSS.

---

## Features

**Shopping Interactions**
- Cart drawer — add, remove, update quantities, subtotal & total
- Wishlist drawer — toggle wishlist, active state indicator
- Quick view modal — image, price, old price, add to cart
- Search popup — filter products by name, suggested categories

**UI & Animations**
- Scroll-reveal animations using native `IntersectionObserver`
- Auto-playing testimonial slider with arrow and dot navigation
- FAQ accordion with smooth height animation and icon rotation
- Toast notifications for cart actions and newsletter form
- Product image hover zoom effect
- Drawer and modal slide-in animation

**Layout & Design**
- Fully responsive — desktop, tablet, and mobile
- Luxury design system — gold accents, serif headings, soft neutral backgrounds
- Component-based React architecture with reusable layout classes
- Semantic HTML and accessible markup

---

## Page Sections

| Section | Description |
|---|---|
| Header | Logo, navigation, search, wishlist, cart, mobile menu |
| Hero | Large image layout, CTA button, decorative elements |
| Categories | Rings, necklaces, earrings with hover effects |
| Story | Brand narrative section with gold background |
| Products | Product cards with quick view, wishlist, cart |
| Services | Brand value propositions |
| Testimonials | Auto-playing customer review slider |
| FAQ | Smooth accordion for common questions |
| CTA Banner | Full-width campaign section |
| Footer | Newsletter, links, social icons, copyright |

---

## Dependencies

Beyond the core stack above, the project also uses:

| Dependency | Type | Usage |
|---|---|---|
| [Ionicons](https://ionic.io/ionicons) | Icon library (CDN) | UI icons across header, cards, and drawers |

No other runtime dependencies are required — everything else is handled by React, Vite, and Tailwind CSS.

---

## Design System

**Colors**

| Token | Hex |
|---|---|
| Primary Gold | `#AD8440` |
| Warm Gold | `#B48A43` |
| Dark Text | `#252525` |
| Deep Black | `#17120D` |
| Soft Background | `#F8F7F5` |

**Fonts** — Source Serif 4 (headings) · Manrope (body, buttons, nav)

**Global layout classes**

```css
.vel-container {
  width: min(calc(100% - 90px), 1360px);
  margin-inline: auto;
}

.vel-section-padding {
  padding-block: 50px;
}
```

---

## Getting Started (Run Locally)

```bash
# Clone the repository
git clone https://github.com/NSniha/jewellery-landing-page.git

# Move into the project folder
cd jewellery-landing-page

# Install dependencies
npm install

# Start the development server
npm run dev
```

```bash
npm run build    # Production build
npm run preview  # Preview the production build
```

Ionicons is loaded via CDN — make sure this is present before the closing `</body>` tag in `index.html`:

```html
<script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
```

---

## Folder Structure

```
jewellery-landing-page/
├── public/
├── src/
│   ├── assets/images/
│   ├── components/
│   │   ├── Header/
│   │   ├── Hero/
│   │   ├── Categories/
│   │   ├── StoryDetail/
│   │   ├── Products/
│   │   ├── Testimonials/
│   │   ├── FAQ/
│   │   ├── LegacyCTA/
│   │   └── Footer/
│   ├── data/products.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

## Responsive Breakpoints

`1199px` · `991px` · `767px` · `575px` · `420px`

---

## Author

**Nobonita Saha Niha** — Frontend Developer

- GitHub: [@NSniha](https://github.com/NSniha)

---

## License

© Nobonita Saha Niha. All rights reserved.

This project is shared publicly for portfolio and reference purposes only. Copying, redistributing, reselling, or using it (in whole or in part) for commercial purposes is **not permitted** without prior written consent.

---

<div align="center">

⭐ If you find this project useful, consider giving it a star — it helps others discover it too.

</div>

