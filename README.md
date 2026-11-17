# aretech.dev

Corporate website for **Arete Tech Development Ltd.**, served with GitHub Pages at https://aretech.dev.

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The whole site (single page, with Privacy/Terms modals) |
| `assets/styles.css` | Compiled Tailwind CSS (committed, so Pages needs no build step) |
| `src/input.css` | Tailwind source |
| `CNAME` | Custom domain for GitHub Pages |
| `favicon.svg` | Browser tab icon |

## Editing

1. Edit `index.html`.
2. If you used Tailwind classes that weren't in the page before, rebuild the CSS:
   ```bash
   npm install
   npm run build
   ```
3. Commit and push to `main`. GitHub Pages republishes within a minute or two.
