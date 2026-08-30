# pedroherrera-catalan.github.io

Personal academic website of Pedro Herrera-Catalán, served at
<https://www.pedroherrera-catalan.com>.

Built with [Jekyll](https://jekyllrb.com/) on the
[Academic Pages](https://github.com/academicpages/academicpages.github.io) template
(a fork of Michael Rose's [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)),
hosted on GitHub Pages.

## Editing content

| What | Where |
| --- | --- |
| Site title, sidebar, social links | `_config.yml` (`author:` block) |
| Top navigation menu | `_data/navigation.yml` |
| Home / bio | `_pages/about.md` |
| CV page | `_pages/cv.md` |
| Publications | one Markdown file per item in `_publications/` |
| Teaching | one Markdown file per course in `_teaching/` |
| Profile photo | replace `images/profile.png` |
| PDFs (CV, papers) | drop into `files/` → served at `/files/<name>.pdf` |
| Custom domain | `CNAME` |

Each publication file uses a `category` of `books`, `manuscripts`, `workingpapers`,
`wip` or `other` (headings defined in `_config.yml` under `publication_category`).

## Local preview (optional)

```
bundle install
bundle exec jekyll serve -l -H localhost
```

Otherwise just push to `main` — GitHub Pages rebuilds the site automatically.
