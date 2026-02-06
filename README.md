# Hugo Blog (GitHub Pages)

## Quick start

1) Add the theme (submodule):

```bash
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

2) Install Hugo Extended (required by PaperMod).

3) Run locally:

```bash
hugo server
```

## Deploy

- Push to `main` and GitHub Actions will build + deploy to GitHub Pages.
- Update `baseURL` in `hugo.toml` to your Pages URL.
