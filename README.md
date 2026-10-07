# Morningstar Group of Canada

Corporate website for Morningstar Group of Canada.

## Local preview

The site uses plain HTML and CSS, with no dependencies, JavaScript, or build step.
Serve the repository root with any static server, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Vercel deployment

Import this repository, select `morningstar-landing-v1`, and use the **Other**
framework preset. Keep the project root at the repository root, leave the build
command empty, and serve the root directory (`.`) as the output directory.
No installation step is needed.

The canonical URL and Open Graph URLs are set to `https://morningstarmgc.ca`.
Connect that domain in Vercel when ready to publish.

## Maintenance

Edit content in `index.html` and layout in `styles.css`. The official brand assets
are referenced directly from `assets/` and must remain unchanged. Navigation,
company links, and email links use native HTML. Smooth scrolling respects the
visitor's reduced-motion preference.
