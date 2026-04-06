# SKYBER — Real Estate Website (Bootstrap Template v2)

A modern, responsive **real estate website template** built with plain **HTML5 + CSS3 + Bootstrap 5**. This project ships as a set of ready-made pages (home, catalog, account, vendor, blog, and support pages) that you can customize and deploy as a static site.

- **Live demo**: [View on GitHub Pages](https://ShuvaMallickPro.github.io/skyber-real-estate-template-v2/)
- **Repository**: [View on GitHub](https://github.com/ShuvaMallickPro/skyber-real-estate-template-v2)

## Features

- **Responsive layout**: built on Bootstrap grid/components
- **Multi-page template**: home, catalog, account, vendor, blog, and utility pages
- **Reusable styling**: structured CSS files for different sections/pages
- **Easy customization**: update content directly in HTML and styles in `css/`
- **Iconography & typography**: Font Awesome + Google Fonts (Poppins)

## Tech stack

- **HTML5**
- **CSS3**
- **Bootstrap 5.2.1 (CDN)**
- **Font Awesome 6 (CDN)**
- **Google Fonts**

## Pages (routes)

- **Home**: `index.html`
- **Catalog**
  - `property-for-rent.html`
  - `property-for-sale.html`
  - `add-property.html` (vendor flow)
- **Account**
  - `personal-info.html`
  - `security.html`
  - `my-properties.html`
  - `wishlist.html`
  - `reviews.html`
  - `notifications.html`
  - `ac-reviews.html`
- **Blog**
  - `blog.html`
- **Company / Support**
  - `about.html`
  - `help-center.html`
  - `contact.html`
- **Error page**
  - `404.html`

## Project structure

```text
.
├─ assets/
│  ├─ fonts/
│  ├─ images/
│  └─ icons.css
├─ css/
│  ├─ style.css
│  ├─ responsive.css
│  ├─ home-v2.css
│  ├─ catalog.css
│  ├─ account.css
│  ├─ vendor.css
│  ├─ pages.css
│  └─ utilities.css
├─ *.html
└─ website-image.png
```

## Getting started (local)

This is a static website—no build step required.

1. **Clone** the repository
2. **Open** `index.html` in your browser (or use a local server)

If you want a local server (recommended for relative paths), you can use any of these:

- VS Code extension: **Live Server**
- Node: `npx serve`
- Python: `python -m http.server`

## Customization

- **Branding**
  - Replace logo/assets in `assets/images/`
  - Update site title/meta in the `<head>` of each page
- **Styles**
  - Global styles: `css/style.css`
  - Responsive tweaks: `css/responsive.css`
  - Page-specific styles: `css/home-v2.css`, `css/catalog.css`, `css/account.css`, `css/vendor.css`, `css/pages.css`
- **Icons**
  - Font Awesome is loaded via CDN in the HTML pages
  - Custom icon set is included in `assets/icons.css`

## Deployment

This project can be deployed to any static hosting platform (GitHub Pages, Netlify, Vercel static export, etc.).

- **GitHub Pages**: deploy the repository and set the source to your default branch (typically `main`).

## Challenges (what I faced)

- **Integrating additional JavaScript packages**: Adding extra JS libraries for UI interactions—like range sliders, layout behaviors, and sidebar show/hide—was challenging in a static, multi-page setup while keeping everything lightweight and consistent.
- **Pixel-perfect implementation**: The main challenge was matching the design **pixel-perfect** based on the _Finder_ theme (purchased from Envato Market), especially spacing, typography, responsive breakpoints, and component alignment across pages.

## Support

If you find a bug or want to request an improvement, please open an issue on the repository:
[Open an issue on GitHub](https://github.com/ShuvaMallickPro/skyber-real-estate-template-v2)
