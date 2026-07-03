# The Signal — Podcast Blog (Beevr demo)

A Jekyll blog hosted on GitHub Pages. Blog posts live in `_posts/` as Markdown
files with YAML front matter (`YYYY-MM-DD-slug.md`).

Beevr publishes new articles here automatically: it transcribes each podcast
episode, drafts an SEO-optimized article from the transcript, and commits it to
`_posts/`. GitHub Pages rebuilds the site on every commit, so new posts go live
within a minute.

## Structure
- `_config.yml` — site config + SEO plugins
- `_posts/` — published articles (one Markdown file per post)
- `about.md` — about page
- `index.md` — home page (lists recent posts)

## Local preview
```bash
bundle install
bundle exec jekyll serve
```
