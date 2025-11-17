# PDFolio Web

A minimalist, browser-based application for creating beautiful, print-ready photography portfolios as PDFs. This is the web version of **PDFolio**, designed to run entirely in your browser with no installation and no sign-up.

## Features

- **Drag & Drop images**
  Add one or many images via the sidebar dropzone to build your portfolio pages.

- **Projects & multi-image series**
  Group images into projects with titles, years, and descriptions.

- **Inline text editing**
  Double-click any text on the page to edit it directly.

- **Style & theme controls**
  Adjust page color, text color, secondary text, and typography presets via the Style panel.

- **Zoom control**
  Use the zoom control overlay to preview pages between 50%–100%.

- **Export as PDF**
  Use your browser's print dialog ("Save as PDF") to export a clean, print-ready PDF.

- **Import / Export JSON**
  Export your portfolio structure as JSON and re-import it later to keep working.

- **Local-only processing**
  Images and text stay in your browser; nothing is uploaded to a server.

## Getting Started

### Option 1: Visit the <Github Page>(https://kabiur-riyad.github.io/pdfolio)

### Option 2: Deploy as a static site

You can host **PDFolio Web** on any static hosting provider (Netlify, Vercel, GitHub Pages, etc.):

1. Upload the contents of this folder (`index.html`, `index.js`, CSS, and `assets/`).
2. Point your host to `index.html` as the entry file.
3. Visit your deployed URL and start building portfolios in the browser.

## Usage Tips

- Drag images into the sidebar dropzone to create pages quickly.
- Use **Add Project** to create multi-image projects with shared metadata.
- Reorder pages with the controls in the sidebar.
- Use **Export JSON** before closing the tab if you want to resume later.
- Click **Save as PDF** and use your browser's **Save as PDF** option in the print dialog.

## For Developers

This web version is a static, client-side application:

- No backend is required.
- The main entry file is `index.html`.
- Core logic lives in `index.js` and styles in `styles.css` / `ui.css`.

You can use any local static file server during development, for example:

```bash
npx serve .
```

Then open the printed URL (often `http://localhost:3000` or similar) in your browser.

## Related Project

- **PDFolio Desktop** – Original desktop application for building PDF portfolios: <https://github.com/kabiur-riyad/PDFolio-Desktop>
