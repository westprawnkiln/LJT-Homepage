# Junteng Liu — Academic Homepage

Personal academic homepage built on the
[Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll theme (a fork of Minimal Mistakes).

## Links

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

## Content structure

- `_pages/about.md` — homepage: biography, academic background, research
  experience, research interests and skills, the full publication list, and
  contact information.
- `_pages/publications.html` and `_publications/` — the publications subpage
  and the individual publication entries.
- `_config.yml` — site-wide settings and author (sidebar) information.

## Local build

```
bundle install
bundle exec jekyll serve
```

The GitHub Actions workflow at `.github/workflows/jekyll.yml` builds the site
with Jekyll and deploys it to GitHub Pages.
