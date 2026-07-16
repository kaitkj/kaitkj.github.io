# kaitkj.github.io

Personal portfolio site, documenting my Hardware Engineering Product Development journey — built with Jekyll, hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000

## Adding content

- **New article** → copy an existing file in `_articles/`, edit the front matter, push.
- **New project** → copy an existing file in `_projects/`, edit the front matter, push.
- **New nav tab** → add a line to `_data/navigation.yml`, create the matching page.

No build step to run manually — GitHub Pages rebuilds automatically on every push to `main`.
