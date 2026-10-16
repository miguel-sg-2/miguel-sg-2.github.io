# Miguel Sanchez Gomez – academic website

A static site (one HTML file, no build step) ready for GitHub Pages.

## Publish on GitHub Pages
1. Create a repository named `<your-github-username>.github.io` (for a personal site at the root URL) or any name (site will live at `/<repo>/`).
2. Upload everything in this folder: `index.html`, `assets/`, `.nojekyll`, `README.md`.
3. In the repository go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-github-username>.github.io/`.

## Things to finish
- **Google Scholar link**: in `index.html`, find `id="scholar-li"`, set the `href` to your profile URL and delete the `hidden` attribute.
- **Your own animations**: each project has `<div class="viz" data-anim="..." data-media="">`. Set `data-media="assets/my-animation.mp4"` (or `.webm`, `.gif`, `.png`) and the built-in schematic is replaced by your file. Add `data-alt="description"` for accessibility.
- **GitHub / LinkedIn links**: add a `<li>` in the sidebar list, copying the ORCID line.
- **Publications**: each entry is a `<li data-tags="...">` in the Publications section; copy one to add a paper. Tags drive the filter buttons.
- **Pending proposals** from the CV were left off on purpose; add them to the funding section when public.

## Credits
Fonts: Newsreader and Instrument Sans (Google Fonts). No frameworks or trackers.
