# GEM Workshop website

This repository contains the source for the GEM workshop website, built with Jekyll and the Minima theme. The site is structured to make the schedule the main page and to provide a Call for Papers page linked from the navigation bar.

How to preview locally:

```powershell
bundle install
bundle exec jekyll serve
```

Notes:
- Pages are simple Markdown files; large tables are wrapped in a responsive container for horizontal scrolling on small screens.
- This site targets GitHub Pages. No additional gems were added beyond the default `github-pages` and `jekyll-feed` in the `Gemfile`.
