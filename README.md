# Personal Blog

A personal blog built with [Jekyll](https://jekyllrb.com/) and the
[Chirpy theme](https://github.com/cotes2020/jekyll-theme-chirpy), based on the
official [Chirpy Starter](https://github.com/cotes2020/chirpy-starter).

## Personalize it

Before publishing, update these values in `_config.yml`:

- `title` and `social.name`
- `tagline` and `description`
- `url` with your final GitHub Pages or custom-domain URL
- `github.username`, `social.email`, and `social.links`
- `avatar` and `social_preview_image` if you want custom artwork

Then edit `_tabs/about.md` and replace the starter post in `_posts/` with your
own story.

## Run locally

1. Install Ruby 3.4 and Bundler (matching the deployment workflow).
2. Run `bundle install`.
3. Run `bundle exec jekyll serve --livereload`.
4. Open <http://127.0.0.1:4000>.

## Write a post

Create a Markdown file in `_posts/` named `YYYY-MM-DD-post-title.md`:

```yaml
---
title: A Useful Post Title
date: 2026-11-03 09:00:00 +0800
categories: [Projects]
tags: [jekyll, notes]
description: A one-sentence summary for search results and social previews.
---
```

Add the article body below the closing `---`.

### Blog tags

Use one or more of these consistent tags in a post's front matter:

```yaml
tags: [Life stuff]
tags: [Mathematics]
tags: [Competitive Programming]
tags: [Cybersecurity/CTFs]
tags: [AI]
tags: [Misc stuff]
```

For multiple tags, combine them into one list:

```yaml
tags: [Mathematics, Competitive Programming]
```

The reusable `_drafts/post-template.md` file contains the same catalog. Chirpy
automatically creates a tag page after a published post uses that tag.

## Publish with GitHub Pages

1. Create a GitHub repository and push this project to its `main` branch.
2. In **Settings → Pages**, choose **GitHub Actions** as the source.
3. Update `url` in `_config.yml` to the deployed address.
4. Push the config change; the included workflow will build and deploy the site.

The deployment workflow lives at `.github/workflows/pages-deploy.yml`.

## License

The starter and Chirpy theme are available under the MIT License. See `LICENSE`.
