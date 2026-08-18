# sumanthbhs.github.io

Personal academic website of **Sumanth Bharadwaj H S**, built with
[Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme
and hosted on GitHub Pages.

**Live site:** https://sumanthbhs.github.io/

## Editing content

| What | File |
| --- | --- |
| Homepage bio & profile | `_pages/about.md` |
| Publications | `_bibliography/papers.bib` |
| CV (education / experience / skills) | `assets/json/resume.json` |
| Social links | `_data/socials.yml` |
| Site title, name, URL, theme options | `_config.yml` |
| News / announcements | `_news/` |
| Profile photo | `assets/img/prof_pic.jpg` |

## How it deploys

Pushing to the `main` branch triggers the **Deploy site** GitHub Action
(`.github/workflows/deploy.yml`), which builds the site and publishes it to the
`gh-pages` branch. GitHub Pages then serves `gh-pages` at the live URL.

## Run locally (optional)

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```
