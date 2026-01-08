# Dovetail (GitHub Pages + Jekyll)

This repo is set up to publish on **GitHub Pages** using **Jekyll** and the **Minimal** theme.

## Theme

Configured in `_config.yml`:

- `theme: jekyll-theme-minimal`

## GitHub Pages settings (on GitHub)

In your repo:

- **Settings → Pages**
- **Source**: “Deploy from a branch”
- **Branch**: `main` (or whichever branch you use)
- **Folder**: `/(root)`

If you’re using the custom domain in `CNAME`, also set the custom domain in **Settings → Pages**.

## Local preview

You’ll need a modern Ruby (GitHub Pages/Jekyll no longer works well with the macOS system Ruby).

Once Ruby 3.x + Bundler are installed:

- `bundle install`
- `bundle exec jekyll serve --baseurl=""`

Then open http://localhost:4000
