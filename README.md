# Jaeho Cho — Personal Web Page

Source of my academic homepage, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template
(forked from Minimal Mistakes; MIT License — see `LICENSE`).

## Editing

| What | Where |
| --- | --- |
| Name, sidebar, links | `_config.yml` (`author:` block) |
| Header menu | `_data/navigation.yml` |
| Home page | `_pages/about.md` |
| CV | `_pages/cv.md` |
| Publications | `_publications/*.md` (one file per paper) |
| Projects | `_portfolio/*.md` |
| Profile photo | `images/profile.png` |
| PDFs | `files/` |

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost   # http://localhost:4000/jaehocho.github.io/
```
or `docker compose up`.
