# DSE 2027 — Academic workshop website

A minimal, accessible, responsive static website for **DSE 2027: 2nd International Workshop on Dark Software Engineering**, co-located with FSE 2027 in Shenzhen, China.

## Design and content

- Restrained academic design: white background, navy text, minimal use of color and no promotional language or decorative hero section.
- Navigation prioritizes researchers' needs: overview, call for papers, dates, submission, organizers, and previous edition.
- Wording follows the accepted proposal. The original simple keyhole symbol is retained in a monochrome vector format.
- Dates from the workshop proposal are provisional pending final FSE instructions. The specific workshop day (12 or 13 July 2027), program committee, schedule, and HotCRP submission portal remain TBA.
- The original HotCRP URL was for the workshop **proposal** and was intentionally not published as a paper-submission link.
- The paper format, planned proceedings, and APC treatment should be confirmed with FSE/ACM before release of the official CFP.

## Run locally

Open `index.html` directly, or run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish to GitHub Pages

1. Create a public repository, for example `dse-2027`.
2. Upload **the contents of this folder**, keeping `index.html`, `styles.css`, and `assets/` at the repository root.
3. In the repository, open **Settings → Pages**. Set **Build and deployment → Deploy from a branch**, with branch `main` and `/ (root)`, and save.
4. GitHub will report the published URL (typically `https://USERNAME.github.io/dse-2027/`).

All paths are relative, so the site works within GitHub's repository subdirectory. No build tools or JS frameworks are required.

## Sources

- Accepted DSE'27 workshop proposal (Kassab, Laplante, Solovey), attached by organizers.
- DSE 2026 workshop materials, attached by organizers.
- FSE 2027: https://conf.researchr.org/home/fse-2027
- DSE 2026: https://conf.researchr.org/home/icse-2026/dse-2026
