# Zixi Wang — academic homepage

Personal website: https://z-702.github.io/

Uses the original [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template, with its default layout, sidebar and publication archive. Typography uses locally bundled Latin Modern Roman, with Times New Roman and Chinese Song-style fallbacks. Font settings and small layout corrections are in `assets/css/custom.css`.

## Edit content

| Content | File |
| --- | --- |
| Name, sidebar, affiliation, links and portrait | `_config.yml` |
| English homepage and education | `_pages/about.md` |
| Chinese homepage | `_pages/about-zh.md` |
| Research | `_pages/research.md` |
| Individual papers, authors, status, summaries and figures | `_publications/*.md` |
| Publication categories and page | `_pages/publications.html` and `_config.yml` |
| Navigation | `_data/navigation.yml` |
| Figures | `images/papers/` |
| BibTeX | `files/*.bib` |

Each paper has its own Markdown file. Set `order` to control homepage ordering and `category` to choose its section on the publications page. Publication status must distinguish published articles, preprints and submissions.

To add a photo, upload it to `images/` and set `author.avatar` in `_config.yml`. The current sidebar has no placeholder portrait.

## Publish

Push to `main`. The GitHub Actions workflow builds and deploys to GitHub Pages automatically. See [DEPLOYMENT.md](DEPLOYMENT.md).

## Local build

With Ruby 3.3 and Bundler:

```sh
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

## Credits

Academic Pages and its MIT license are retained. See [UPSTREAM.md](UPSTREAM.md). Latin Modern font files are distributed unmodified with their GUST license and original documentation under `assets/fonts/latin-modern/`. Research figures belong to the corresponding papers. The unpublished CT submission PDF and cover letter are not included.
