# Repository Guidelines

This repository builds a personal academic homepage with Jekyll and GitHub Pages. Content is written in Markdown with YAML front matter; styling uses SCSS. Pushing to the default branch triggers an automatic GitHub Pages build.

## Project Structure

- `_pages/` — Markdown site content (e.g., `about.md`).
- `_layouts/` and `_includes/` — HTML templates and reusable components (sidebar, masthead).
- `_sass/` and `assets/` — Theme SCSS and compiled CSS/JS/fonts.
- `_data/` — Site data, including `navigation.yml`.
- `images/` — Photos and icons referenced from content.
- `files/` — Public downloads (CV, patents, transcripts).
- `docs/` — Project documentation, such as `README-zh.md`.
- `google_scholar_crawler/` — Standalone Python script for citation stats (see Automation).

## Build and Development Commands

```bash
bundle install              # Install Ruby dependencies from Gemfile
bundle exec jekyll serve    # Build and serve at http://127.0.0.1:4000
bundle exec jekyll build    # Build the site into _site/ without serving
```

There is no automated test suite; verification is a clean local build and manual preview.

## Coding Style and Naming Conventions

- Use 2-space indentation in YAML, HTML, and SCSS; 4 spaces in Python.
- Use `snake_case` for files and variables; SCSS partials use a leading underscore (`_sass/_masthead.scss`).
- Start every page in `_pages/` with YAML front matter: `permalink`, `title`, `author_profile`, and `redirect_from` when needed.
- Do not hand-edit compiled outputs (`assets/css/*.css`, `assets/js/main.min.js`); change sources only.

## Testing Guidelines

No unit-test framework is configured. Before pushing, run `bundle exec jekyll build` and confirm it exits cleanly, then check affected pages for broken links and images.

## Commit and Pull Request Guidelines

History uses short, descriptive messages in Chinese or English (e.g., "同步最新简历和成绩单", "修改比赛获奖"), with release tags such as `v1.1.5`. Follow that style and keep each commit focused.

Open a pull request for non-trivial changes: describe what changed and why, verify the local build, and include a screenshot for visual changes. Link related issues when applicable.

## Automation

`.github/workflows/google_scholar_crawler.yaml` runs `google_scholar_crawler/main.py` daily at 08:00 UTC and after each Pages build, pushing citation JSON to the `google-scholar-stats` branch. It requires the `GOOGLE_SCHOLAR_ID` secret; do not commit crawler output to the main branch.

## Configuration Tips

Keep `_config.yml` accurate (site title, author, `repository`). Files placed in `files/` are public, so only add documents intended for public download.
