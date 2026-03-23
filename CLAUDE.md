# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Personal GitHub Pages site hosted at `https://rm-kay.github.io`. The repository is in early stages — no build system or site content exists yet.

## GitHub Pages

GitHub Pages automatically serves static content from the `main` branch. To add a site:
- A plain `index.html` at the root will be served directly with no build step required.
- For a static site generator (Jekyll, Hugo, Eleventy, etc.), add a build workflow under `.github/workflows/` and configure Pages to deploy from the Actions output.

Jekyll is natively supported by GitHub Pages with zero configuration — adding a `_config.yml` and Markdown files is enough to get a site live without a custom workflow.
