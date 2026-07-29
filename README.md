# West Toronto Chinese Bible Church

This repository contains the bilingual website for West Toronto Chinese Bible Church (WTCBC), published with GitHub Pages at [wtcbc.com](https://www.wtcbc.com).

## Updating the site

- Church details and external links are in `_data/settings.yml`.
- Chinese pages are in the repository root.
- English pages are in `en/`.
- Shared navigation and footer content are in `_includes/`.
- Site photos are in `assets/img/site/`.
- Older sermon posts remain in `_posts/`.

The site is built with Jekyll and does not require a hosted website builder or database. Pushing a change to the publishing branch will trigger a GitHub Pages rebuild.

## Local preview

With a current Jekyll installation:

```sh
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
