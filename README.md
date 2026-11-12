# The Economic Historian

Jekyll site for GitHub Pages. No plugins beyond what GitHub Pages ships, so it builds from the branch with no workflow.

## Publish

1. Create a repository and push these files to `main`.
2. Settings, Pages: source "Deploy from a branch", branch `main`, folder `/ (root)`.
3. `_config.yml` is set for https://atrevidoantonio.github.io/economichistorian/ (`baseurl: "/economichistorian"`). If you move the site to a custom domain, set `url` to that domain and `baseurl` to `""`.

## Add an essay

Create `_essays/<slug>.md`:

```
---
title: "Title"
subtitle: "Standfirst"
author: "Author Name"
date: 2026-11-11
section: "Money and finance"
substack: substack-post-slug
featured: true
---

Essay text in Markdown.
```

- With body text, the essay is published on this site.
- With no body, every listing links to the Substack post at `substack_url/p/<substack>`.
- `featured: true` puts the essay on the cover. Without it the newest essay leads.
- `section` must match an entry in `_data/sections.yml`.

## Preview locally

```
bundle install
bundle exec jekyll serve
```

## Where things are

```
_config.yml           title, tagline, editors, Substack address
_data/sections.yml    subject list and its order
_essays/              one file per essay
_layouts/             default, essay, page
_includes/            header, footer, essay link logic
assets/css/site.css   all styling
index.html            cover, recent essays, subjects, subscribe
essays.html           archive with subject filter
about.md, submissions.md
```
