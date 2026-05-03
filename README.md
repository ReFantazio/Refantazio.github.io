# Yunpeng Li Academic Homepage

This repository contains a GitHub Pages academic homepage based on the Minimal Light Jekyll theme.

## Edit Content

- Basic profile, links, SEO text: `_config.yml`
- Homepage sections: `index.md`
- Publication list: `_data/publications.yml`
- Academic profile links: `_includes/services.md`
- Header and social icons: `_layouts/homepage.html`
- Avatar and publication cards: `assets/img/`

## Deploy To GitHub Pages

1. Create a GitHub repository named `YOUR-GITHUB-USERNAME.github.io`.
2. Push this repository to GitHub.
3. In GitHub, open `Settings` -> `Pages`.
4. Set the source to the default branch and root folder.
5. Visit `https://YOUR-GITHUB-USERNAME.github.io/` after the Pages build finishes.

## Local Preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

The local site will be available at `http://localhost:4000/`.

## Attribution

This site is adapted from [Minimal Light](https://github.com/yaoyao-liu/minimal-light), which is licensed under CC0-1.0.
