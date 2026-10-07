Brand artwork. Three independent slots, all resolved at build time by
`components/app-shell/brand.tsx` — drop a file here and rebuild, no code change.

`biobox-wordmark.svg`
  The wide "BIOBOX" lockup (DNA double helix as the "i"), shown in the sidebar
  header next to the primary navigation. Transparent background, 3 flat greens
  (#14451b / #266630 / #229c35), intrinsic size 3018x622.
  Without it the header falls back to the square mark alone.

`biobox-wordmark-on-dark.svg`
  The same geometry with the greens lightened (#4b8b51 / #58af61 / #65d371),
  served automatically under `dark:`. The original tones only reach 1.7:1 for the
  darkest letter on the dark sidebar (#111111); the lightened set reaches
  4.6:1 / 6.9:1 / 10.0:1 while keeping the hue and the three-tone structure.
  Delete this file to use the original artwork in both themes.

`logo.svg` (preferred), `logo.png`, `logo.webp`
  A SQUARE mark, transparent, readable at 32px. It replaces the DNA placeholder
  tile that is shown on the collapsed sidebar rail.

To change the browser tab icon, replace `app/icon.svg`.
