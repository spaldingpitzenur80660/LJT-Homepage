# LJT-Homepage

Personal academic homepage of **Junteng Liu**, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template for GitHub Pages.

## Contents

* **About** (`_pages/about.md`) - personal details, research interests, education, research experience, publications, awards and contact information.
* **Publications** (`_pages/publications.html`, `_publications/`) - one Markdown file per paper.
* **CV** (`_pages/cv.md`) - education, research experience, research interests, publications, awards and contact information.

Site-wide settings (name, sidebar, contact links, Google Scholar) live in `_config.yml`, and the header menu is defined in `_data/navigation.yml`.

## Publishing the site

The site is built and deployed by the GitHub Actions workflow in `.github/workflows/jekyll.yml`, which runs on every push to `master`.

One-time setup: GitHub Pages has to be switched on for the repository by its owner, because the workflow token is not allowed to create the Pages site itself. Go to **Settings -> Pages** and set **Build and deployment -> Source** to **GitHub Actions**, then re-run the workflow. The site will then be published at `https://spaldingpitzenur80660.github.io/LJT-Homepage/` (the `url` and `baseurl` values in `_config.yml` match this address).
