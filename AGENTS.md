# Repository Guidelines

## Project Structure & Module Organization
This repository is a Jekyll-based GitHub Pages site for a personal academic homepage, but routine updates should be limited to [`_pages/about.md`](/Users/wangshigeng/genggng.github.io-V2/_pages/about.md). That file contains the main profile, news, publications, and links. Other directories such as `_layouts/`, `_includes/`, `assets/`, and `images/` exist for the site theme, but they are normally out of scope for contributor edits. Do not edit `_site/`; it is generated output.

## Build, Test, and Development Commands
- `git status`: confirm that only `_pages/about.md` is being changed.
- `git diff -- _pages/about.md`: review the exact content update before committing.
- `git push origin master`: publish the change to the GitHub Pages branch.

This repository deploys from pushes to `master`. Local build or test steps are not required for the normal content-only workflow used here.

## Coding Style & Naming Conventions
Edit in Markdown and follow the existing style in `_pages/about.md`. Keep entries concise, preserve the current bullet-list format for publications and updates, and use inline links directly in Markdown, for example `[paper](https://arxiv.org/abs/2604.12391)`. Keep names, venues, and dates consistent with nearby entries. Avoid reformatting unrelated sections.

## Testing Guidelines
There is no required local test step for the current workflow. Validation is lightweight: check the Markdown diff, verify URLs are correct, and make sure the edit stays within `_pages/about.md`.

## Commit & Pull Request Guidelines
Recent commit messages are short and action-focused, for example `add cvpr`, `update sliderquant code link`, and `Update publication links on about page`. Follow the same pattern and keep each commit scoped to one content update. If a pull request is used, keep it brief: summarize what changed in `about.md` and include the relevant link or publication reference.
