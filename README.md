# hakhyun0615.github.io

Personal academic website of Hak Hyun Kim, M.S. student in Computer Science at Dartmouth College.

Built with [al-folio](https://github.com/alshedivat/al-folio), a Jekyll theme for academics.

## Local development

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Requires Ruby 3.3.5 (pinned in `.ruby-version`) and ImageMagick for responsive images.

## Where content lives

| What                       | File                               |
| -------------------------- | ---------------------------------- |
| Homepage bio               | `_pages/about.md`                  |
| Publications               | `_bibliography/papers.bib`         |
| News items                 | `_news/`                           |
| Teaching                   | `_pages/teaching.md`               |
| Site config, name, socials | `_config.yml`, `_data/socials.yml` |

The personal CV is maintained privately outside this repository. Do not add CV PDFs or source files to the public website.
