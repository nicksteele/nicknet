# Nick Steele — nicksteele.net

Based on Academic Pages (MIT). See LICENSE and UPSTREAM.md. Font license is
assets/fonts/OFL.txt. Theme footer attribution is retained.

## Content

Edit _pages/about.md for the bio and _config.yml for profile links.
Add Markdown posts under _posts/YYYY-MM-DD-slug.md with title/date front matter.
Add Markdown projects under _portfolio/slug.md with title/excerpt front matter.
Blog and project indexes populate automatically; no demo entries are included.

## Build

Ruby 4.0.7, Bundler, and the committed Gemfile.lock:

```sh
bundle install
bundle exec jekyll build
```

GitHub Pages Actions builds and deploys only the repository default branch.
Select GitHub Actions in repository Settings → Pages. The custom domain is
nicksteele.net. Configure this domain in Pages settings, verify ownership using
GitHub's account Pages settings, and enable HTTPS after DNS/certificate readiness.
Retain Squarespace nameservers and all Google mail records. Only web-hosting DNS
records should change. No credentials or local drafts belong in this repository.
