# About-Card

A lightweight personal profile card built with plain HTML, CSS, and JavaScript. The page displays profile information, social links, action buttons, a dropdown menu, and a light/dark theme toggle.

## Features

- Single-page personal "about card" layout
- Theme toggle (light/dark mode)
- Dropdown quick-links menu
- Social/media icon links via Font Awesome
- Responsive card sizing for smaller screens
- Zero build step (static files only)

## Tech Stack

- **HTML5**
- **CSS3** (custom properties, media query, component styling)
- **JavaScript (ES6)** with **jQuery** for DOM-ready/menu interaction
- External assets:
  - Font Awesome (CDN)
  - Google Fonts (CDN)

## Project Structure

```text
.
├── index.html      # Markup for profile card and links
├── style.css       # Theme variables, layout, responsive styles
├── main.js         # Menu toggle + theme toggle behavior
├── img/
│   ├── icon.jpg    # Favicon
│   ├── logo.jpg    # Profile image
│   ├── dbg.jpg     # Default background
│   └── lbg.jpg     # Alternate background (dark mode)
├── LICENSE         # Apache-2.0
└── README.md
```

## Prerequisites

You only need a modern web browser.

## Run Locally

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Serve as a local static site (recommended)

From the repository root:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Customization

To adapt this card for your own profile:

1. Update identity text, links, and contact details in `index.html`.
2. Replace images inside `img/` (`logo.jpg`, `icon.jpg`, backgrounds).
3. Adjust colors and theme variables in `style.css` (`:root` and `.dmode`).

## Deployment

This project is static and can be deployed to any static host (for example GitHub Pages, Netlify, or Vercel static hosting).

Generic deployment flow:

1. Push this repository to GitHub.
2. Configure your host to publish from the repository root.
3. Set `index.html` as the entry page (default for most static hosts).

## Limitations

- No backend/API integration
- No package manager scripts, linting, or automated test setup included

## License

Licensed under the Apache License 2.0. See [`LICENSE`](./LICENSE).
