# Haoyun Zhang — Academic Homepage

Personal academic website for Haoyun Zhang, an M.S. student in Biomedical Engineering at the University of Michigan. The site is based on the open-source [WowPage](https://github.com/WD7ang/WowPage) Jekyll template and has been redesigned around research in clinical AI, multimodal learning, computational biology, and medical imaging.

## Local preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/`.

## Content map

- `_config.yml` — identity, email, profile links, site URL, and repository name
- `_pages/about.md` — all homepage copy and section content
- `assets/css/home.css` — homepage design system and responsive layout
- `images/` — profile and research visuals
- `files/Haoyun_Zhang_CV.pdf` — downloadable CV
- `_data/navigation.yml` — top navigation

## Deploy with GitHub Pages

1. Create a repository named `HaoyunZhang2003.github.io` under the `HaoyunZhang2003` GitHub account.
2. Push this project to the repository's `main` branch.
3. In **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. The site will be available at `https://haoyunzhang2003.github.io` after the first build finishes.

If deploying as a project site under a different repository name, update `url`, `baseurl`, and `repository` in `_config.yml`.
