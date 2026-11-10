# Xiaoqi Lin — personal academic website

Live at https://rosalynn7.github.io

Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and hosted free on GitHub Pages.

## Where things live

| To change…                     | Edit                                   |
| ------------------------------ | -------------------------------------- |
| Name, site URL, SEO keywords   | `_config.yml` (top of file)            |
| Bio / home page                | `_pages/about.md`                      |
| Headshot                       | replace `assets/img/prof_pic.jpg`      |
| Publications                   | `_bibliography/papers.bib`             |
| Presentations                  | bottom of `_pages/publications.md`     |
| Research project pages         | `_projects/*.md`                       |
| News items (home page)         | `_news/*.md` (one file per item)       |
| CV page                        | `_data/cv.yml`                         |
| CV PDF                         | replace `assets/pdf/Xiaoqi_Lin_CV.pdf` |
| Email / GitHub / Scholar icons | `_data/socials.yml`                    |

Every push to `main` rebuilds and redeploys the site automatically (about 3–5 min). You can watch it under the repo's **Actions** tab.

## Still to do (optional)

Search the repo for `TODO`: add your Google Scholar ID / ORCID / LinkedIn in `_data/socials.yml`, and check the dates on two news items in `_news/`.

## Preview locally (optional)

With Docker installed: `docker compose up`, then open http://localhost:8080.
