<!-- SPDX-FileCopyrightText: 2026 the Folio Project -->
<!-- SPDX-License-Identifier: MIT -->

# Folio Suite developer homepage

This is a small static HTML and CSS homepage for Folio Suite developer resources. It has no build step, framework, external fonts, analytics, CMS, or backend.

## GitHub Pages

The organization root repository is `Folio-Suite/folio-suite.github.io`, served from the repository root. Publish the default branch with GitHub Pages branch publishing; GitHub Actions are not required. `.nojekyll` keeps Pages from applying Jekyll processing.

The UndoKit documentation link is `/UndoKit/`, which works at both the organization `github.io` root and the `foliosuite.dev` root. The custom domain is configured in GitHub Pages settings. DNS is managed separately through Porkbun; domain verification and HTTPS must be checked during a cutover.

## Files

- `index.html` — accessible, responsive homepage and project links.
- `style.css` — local presentation; system fonts only.
- `.nojekyll` — disables Jekyll processing on GitHub Pages.
- `LICENSE` — MIT license.
