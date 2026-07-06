# TENCITY — homepage mockup (Phase 1)

A static, DS-Mineralöl-style redesign concept for the TENCITY homepage, built from
the real TENCITY brand tokens (navy `#143346`, green `#59B171`, Circe / Helvetica Neue).
This is a design preview only — tokens and components map 1:1 to the planned WordPress
block theme.

## View it
Open `index.html` in any browser. All images are bundled in `assets/`.

## Live preview (GitHub Pages)
Enable **Settings → Pages → Deploy from branch → `main` / root**.
Your preview will be served at `https://<user>.github.io/<repo>/`.

## Note on fonts
The headings use TENCITY's real **Circe** font, loaded via `@font-face` from
`tencity.at`. If cross-origin loading is blocked, headings fall back to Helvetica/Arial.
To guarantee Circe everywhere, add the `Circe-*.woff2` files to `assets/fonts/`
and point the `@font-face` rules at them.
