# Fawwaz Website

Personal GitHub Pages website for Fawwaz Alfarizqi Mukti Wibowo.

The site is a playful, space-themed single-page profile with favorite collections, skills, artwork, and a small journey timeline.

## Features

- Dark outer-space hero section with photo frame and floating space icons
- Responsive layout for desktop, tablet, and mobile
- Language switcher for Indonesian, English, and Chinese
- Favorite collection cards: fan, planets, outer space, and ABC Lore
- Skill cards with hover animation
- Artwork gallery using local assets
- Journey timeline with numbered milestone cards

## Project Structure

```text
.
├── index.html
├── assets/
│   ├── foto.webp
│   ├── kipas.webp
│   ├── planet.webp
│   ├── blackhole.webp
│   └── icons/
└── README.md
```

## Local Preview

Because this is a static HTML site, you can open `index.html` directly in a browser.

If you prefer a local server:

```bash
python3 -m http.server 8081
```

Then open:

```text
http://localhost:8081
```

## Deployment

This repository is intended for GitHub Pages:

```text
https://fawwaz-alfarizqi.github.io
```

Push changes to the `main` branch, then GitHub Pages will serve the site from the repository root.

## Notes

- Main content and styling live in `index.html`.
- Images are stored in `assets/`.
- Icons are stored in `assets/icons/`.
- `.DS_Store` is ignored via `.gitignore`.
