# VENEESH BOREWELLS Website

This repository contains a static single-page website (`index (2).html`).

## Vercel hosting

The requested `npx plugins add vercel/vercel-plugin` flow is not applicable here because this repository has no package manager setup or plugin-based build system.

For Vercel deployment, use the included `vercel.json`:

- No build step is required.
- The site is served as static content.
- All routes are rewritten to `index (2).html` so the single-page site loads from `/` and deep links.
