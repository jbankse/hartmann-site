# Fonts

Self-hosted fonts for the Hartmann-Schröder website.

## Directory Structure

```
fonts/
├── newsreader/   → Used for the logo wordmark
└── inter/        → Used for all body text, headings, and UI elements
```

## Setup

Drop your `.woff2` and/or `.woff` font files into the corresponding directories.

### Expected files for `newsreader/`

| File | Weight | Style |
|------|--------|-------|
| `Newsreader-Regular.woff2` | 400 | normal |
| `Newsreader-Italic.woff2` | 400 | italic |
| `Newsreader-Bold.woff2` | 700 | normal |

### Expected files for `inter/`

| File | Weight | Style |
|------|--------|-------|
| `Inter-Regular.woff2` | 400 | normal |
| `Inter-Medium.woff2` | 500 | normal |
| `Inter-SemiBold.woff2` | 600 | normal |
| `Inter-Bold.woff2` | 700 | normal |

> **Note:** `.woff2` is the preferred format for modern browsers. Include `.woff` as a fallback if needed. Update the `@font-face` declarations in `styles.css` if you add or rename any font files.
