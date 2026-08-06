# OCPC website

This repo contains sources for https://ocpc.camp/.

To serve the website locally, checkout the repo and run:

```sh
cd docs
jekyll serve
```

The site will be served at http://127.0.0.1:4000.

## Archiving

1. Go to `/docs`.
2. Move all `*.html` files to archive subdirectory.
3. Add `<b>You are viewing an archived website for a previous edition of the camp. Click <a href="/">here</a> to access the website for the current camp.</b>` to the archive's `before.html`.
4. Make a new subdirectory in `_data` and update `site.data` links in the most up to date version of the site.

