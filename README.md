# Hartmann-Schröder — Website

A static HTML website for Hartmann-Schröder.

## Project Structure

```
web/
├── index.html      → Main page
├── styles.css      → All styling
├── fonts/          → Self-hosted font files
│   ├── newsreader/ → Logo wordmark font
│   ├── inter/      → Body / UI font
│   └── README.md   → Font setup instructions
└── README.md       → This file
```

## Getting Started

1. Drop your font files into `fonts/newsreader/` and `fonts/inter/` (see `fonts/README.md` for details).
2. Open `index.html` in a browser.

## Fonts

- **Newsreader** — Used exclusively for the company logo wordmark.
- **Inter** — Used for all other text (headings, body, navigation, footer).

Until the font files are added, the site will fall back to system serif (for the logo) and system sans-serif (for everything else).

## Customization

- Edit the bullet-point content in the `<main>` section of `index.html`.
- Update the placeholder address, phone, and email in the `<footer>`.
- Replace the Privacy Policy and Terms of Service `href` values with real URLs.
- Replace the Instagram and LinkedIn `href` values with your actual profile URLs.
