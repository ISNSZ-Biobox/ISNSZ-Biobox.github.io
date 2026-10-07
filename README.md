# isnsz-biobox.github.io

The published Biobox site, served by GitHub Pages at <https://isnsz-biobox.github.io/>.

**This branch is generated — do not edit it by hand.** Every deploy replaces it wholesale
with the output of `pnpm build` from
[`ISNSZ-Biobox/Biobox`](https://github.com/ISNSZ-Biobox/Biobox) (branch `biobox-nextjs`),
run by `.github/workflows/deploy-pages.yml` in that repository. Anything committed here is
overwritten by the next deploy.

- Source code, content, issues and pull requests:
  <https://github.com/ISNSZ-Biobox/Biobox>
- To change the site, edit that repository and push to `biobox-nextjs` — the deploy runs
  itself. A manual run is available from the **Actions** tab of that repository.

## Why there is a `.nojekyll` file here

GitHub Pages runs Jekyll over whatever it publishes unless a `.nojekyll` file tells it not
to, and Jekyll drops every directory whose name begins with `_`. Next.js puts its entire
client bundle and stylesheet under `_next/`, so without that file the site publishes and
then renders as unstyled HTML with no JavaScript.

## Licence

- **Code** — MIT, see [`LICENSE`](./LICENSE).
- **Content** (the biology entries, worksheets and prose) — CC BY 4.0, see
  [`LICENSE-CONTENT`](./LICENSE-CONTENT).
