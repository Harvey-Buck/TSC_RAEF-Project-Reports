# TSC_RAEF Project Reports

Tractor Supply Raeford project reports and coordination briefs.

## Published Construction Report

- [Open Construction Status](https://harvey-buck.github.io/TSC_RAEF-Project-Reports/construction-status.html)
- [Site root](https://harvey-buck.github.io/TSC_RAEF-Project-Reports/) redirects to the construction report.

The current construction report is issued October 2, 2026.

## GitHub Pages Setup

Pages uses GitHub Actions. The `Deploy construction report` workflow stages only
`index.html` and `construction-status.html` for publication. It runs when those
files or the workflow change on `main`, and can also be dispatched manually.

GC, civil, and internal coordination reports remain repository files and are
excluded from the Pages deployment. This repository is public; exclusion from
Pages does not make repository files private.

To update the published construction report, edit `construction-status.html`,
commit, and push to `main`. Preserve the root redirect in `index.html`.
