# Simon Stender – Design Portfolio

Static GitHub Pages site for `portfolio.simonstender.de`.

## Structure

- `index.html` – complete self-contained landing page
- `assets/` – case-study preview images
- `files/` – case-study PDFs
- `CNAME` – GitHub Pages custom-domain configuration

No build step or dependencies are required. Commit the files to the branch used by GitHub Pages and deploy from the repository root.

## Public CV

- `cv/index.html` – noindex CV landing page
- `cv/Simon-Stender-CV.pdf` – sanitized public CV PDF
- `robots.txt` – points crawlers to the sitemap
- `sitemap.xml` – intentionally lists only the main portfolio page

The CV is still publicly accessible to anyone with the URL. The CV landing page uses `noindex` to reduce discoverability, but this is not access control.
