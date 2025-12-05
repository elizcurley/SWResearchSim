# Social Work Research Lab Simulation

This repository contains a single-page, fully client-side simulation that walks students through PI-level research choices in a social work context.

## Files
- `index.html`: authoritative source for the simulation at the repository root. Deploy this when your host serves from the root of the default branch (e.g., GitHub Pages on `main`).
- `dropin/index.html`: convenience copy of the same file for one-click/static hosts (e.g., Netlify Drop) or when your site expects content from a `docs/` folder. It mirrors the root file; you do not need to delete either copy.

## Deployment
- **Branch:** Deploy from your default branch (typically `main`). If you use GitHub Pages, point it to the root of `main` or to a `docs/` folder containing the drop-in copy.
- **No build step:** Everything is in the HTML file—just upload or push the desired copy to the branch/folder your host serves.
- **Avoid blanks:** Ensure your host serves the HTML file from the site root (or configured folder) so the page loads instead of a blank directory listing.
