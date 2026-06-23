# Sushi — Restaurant Landing Page

A modern, responsive landing page for a Japanese sushi restaurant. Built with
semantic HTML, modular CSS, and vanilla JavaScript, bundled with **Vite** and
animated on scroll with **AOS**.

## ✨ Features

- Fully responsive layout (mobile → desktop)
- Smooth scroll-reveal animations (AOS)
- Modular CSS organised per section
- Dynamic content rendered with vanilla JavaScript
- Optimised image assets bundled through Vite

## 🛠️ Tech Stack

- HTML5
- CSS3 (modular, per-section structure)
- JavaScript (ES Modules)
- [Vite](https://vitejs.dev/) — build tool & dev server
- [AOS](https://michalsnik.github.io/aos/) — animate on scroll

## 🚀 Getting Started

```bash
# install dependencies
npm install

# start the dev server
npm run dev

# build for production
npm run build

# preview the production build
npm run preview
```

The dev server runs at `http://localhost:5173` by default.

## 📁 Project Structure

```
.
├── assets/        # images & icons
├── css/           # global + per-section styles
│   └── sections/
├── js/            # JavaScript modules
├── public/        # static files served as-is
└── index.html     # entry point
```

## 📦 Build & Deploy

The site is a static build produced by Vite. Run `npm run build` and deploy the
generated `dist/` directory to any static host (Netlify, Vercel, GitHub Pages, …).

---

Built by **FilipKalcic1**.
