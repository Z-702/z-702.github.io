# Zixi Wang — personal academic homepage

A personalized [Academic Pages](https://github.com/academicpages/academicpages.github.io) website for **Z-702.github.io**.

## Content

- Undergraduate in Electronic Information Engineering, UESTC.
- Research in AI for neuroimaging, white matter tractography, multimodal registration, and 3D medical image analysis.
- Three research works with method figures, author lists, publication status, bilingual summaries, and available citations.
- English/Chinese language switching, light/dark theme support, and responsive layouts.

The website name follows the supplied papers' author name, **Zixi Wang**. The undergraduate status follows the current request. No unconfirmed email, CV, scholar profile, degree dates, or awards are included.

## Publish

See [DEPLOYMENT.md](DEPLOYMENT.md). Create `Z-702/Z-702.github.io`, upload this project's contents, and set **Settings → Pages → Source → GitHub Actions**. The workflow builds the Jekyll site and publishes it.

## Edit

| What to change | File |
| --- | --- |
| Name, affiliation, public links | `_config.yml` |
| About and education | `_pages/about.md` |
| Research descriptions | `_pages/research.md` |
| Publications | `_includes/selected-publications.html` |
| Summaries, translations, BibTeX | `assets/js/personal.js` |
| Method figures | `images/papers/` |
| Navigation | `_data/navigation.yml` |
| Visual overrides | `assets/css/personal.css` |

To add a portrait, upload your image to `images/` and change `author.avatar` in `_config.yml`. The current image is an initials graphic.

## Local build

With Ruby 3.3 and Bundler installed:

```sh
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

Keep generated `_site/`, `vendor/`, and `.bundle/` out of source control.

## Credits

Original Academic Pages theme and MIT license are retained. See [UPSTREAM.md](UPSTREAM.md) for source provenance. Method figures belong to the corresponding research papers. This repository does not redistribute the unpublished CT manuscript or its submission cover letter.
