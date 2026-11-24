# Academic portfolio — Divinegift J. Chimere

Static HTML/CSS/JS; no build step, dependencies or external fonts.

## Preview
Open index.html in a browser, or run `python -m http.server 8000` from this directory and visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a repository (e.g. `yourusername.github.io` or `academic-portfolio`).
2. Upload the contents of this directory, including assets and .nojekyll, to the repository root.
3. In Settings → Pages, select Deploy from a branch, main, / (root), then Save.
4. Open the URL displayed by GitHub Pages after deployment. Relative links support both user and project sites.

## Before publishing
- The supplied CV is copied unchanged and contains personal phone and location information. Replace it with a public-facing version if desired; keep the filename or update links across pages.
- The supplied CV lists University of Ottawa and Covenant University; these take precedence over conflicting older conversation details. Verify degree history and current teaching appointment dates.
- Review all three teaching PDFs for student privacy, third-party imagery and publication permission. They are supplied unchanged. Remove or replace assets if necessary.
- Confirm professional memberships, conference caption, research status and institutional affiliation. Obtain advisor/group approval before releasing unpublished results, protocols or datasets.
- Add verified publication DOIs, ORCID, Google Scholar, institutional email, advisor/group link and a public data repository when available. No unverified identifiers are included.
- Add anonymized student feedback, sample syllabi, assessment rubrics and service evidence as they become available. Distinguish teaching experience from course readiness.
- Edit page content directly in HTML. Shared visual tokens are at the top of style.css. Navigation/footer are repeated in each page; update consistently. Theme preference is stored locally in the browser.
- Accessibility: semantic landmarks, skip links, focus states, image alternatives, reduced motion and responsive layouts are implemented; perform browser, keyboard, screen-reader and contrast audits before claiming WCAG AA compliance.

## Structure
index.html — home; research.html — research overview; fractionation.html, charging.html, materials.html — project detail; teaching.html — philosophy and evidence; service.html — leadership; about.html — education, industry and CV; assets/ — supplied media and documents; style.css — shared design; theme.js — theme toggle.
