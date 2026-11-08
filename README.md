# eduardwikarta.github.io

Personal academic website of Eduard Wikarta, built with the
[Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template
(MIT licence, see `LICENSE`). It is served at <https://eduardwikarta.github.io>.

## Where things are

| What | File |
|---|---|
| Name, sidebar bio, links (Scholar, ORCID, email ...) | `_config.yml` (the `author:` block) |
| Header menu | `_data/navigation.yml` |
| Home page | `_pages/about.md` |
| Code, Contact, CV pages | `_pages/code.md`, `_pages/contact.md`, `_pages/cv.md` |
| Publications | one file per paper in `_publications/` (copy `_templates/publication.md`) |
| Talks and posters | one file per talk in `_talks/` (copy `_templates/talk.md`) |
| PDFs (CV, papers, slides) | `files/` → served at `/files/<name>.pdf` |
| Profile photo | `images/profile.png` (square, about 400 × 400 px) |

Open placeholders are marked `TODO` (search for it).

## Publishing

Every push to `main` runs `.github/workflows/jekyll.yml`, which builds the site and deploys it to
GitHub Pages. In the repository settings, **Pages → Build and deployment → Source** must be set to
**GitHub Actions**. A build takes 1–2 minutes; check progress in the *Actions* tab.

Only post material that is already public (published papers, preprints, public talks, open-source
code).
