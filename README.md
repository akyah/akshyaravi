# Akshya Ravi Portfolio

This folder contains the files for a GitHub Pages portfolio website.

## Files

- `index.html` - main website page
- `styles.css` - website styling
- `script.js` - mobile menu and small page interactions
- `assets/` - resume PDF, project preview images, project PDFs, and profile photo

## How to edit

Most edits happen in `index.html`.

- Change section text by editing the words between the HTML tags.
- Add a clickable article by copying one publication block in the `Publications` section.
- Change the article link by replacing the value inside `href="..."`.

Example clickable article:

```html
<a class="publication-link" href="https://example.com/article" target="_blank" rel="noreferrer">
  <span class="publication-type">Journal article</span>
  <strong>Article Title Goes Here</strong>
  <span>Journal name, year</span>
</a>
```

## How to publish on GitHub Pages

1. Open your repository: `https://github.com/akyah/akyah.github.io`
2. Upload everything in this folder to the repository root.
3. Make sure `index.html`, `styles.css`, `script.js`, and `assets/` are not inside another nested folder after upload.
4. Commit the files.
5. Go to Settings > Pages.
6. Set the source to deploy from the `main` branch and the repository root.
7. Your site should appear at `https://akyah.github.io` after GitHub finishes publishing.
