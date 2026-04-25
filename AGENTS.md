# Agent Instructions

## Overview
This is a [Quarto](https://quarto.org/) website for Alexander Senetcky. Content is authored in `.qmd` files and rendered to HTML in the `docs/` directory.

## Core Workflow
- **Render Site**: Uses Quarto to render `.qmd` files into the `docs/` directory.
- **Content**: New posts, pages, or presentations should be written as `.qmd` files.
- **Deployment**: The `docs/` directory contains the static site output.

## Developer Commands
- **Render site**: `quarto render` (renders the entire project)
- **Render specific file**: `quarto render <file>.qmd` (useful for testing changes to a single page)
- **Preview site**: `quarto preview` (starts a local server with live reload)

## Architecture & Directory Structure
- `_quarto.yml`: Main configuration for the Quarto project (navbar, theme, etc.).
- `*.qmd`: Quarto Markdown files containing the actual content.
- `docs/`: The output directory for the rendered site. **Do not manually edit files in `docs/`**.
- `posts/`: Directory for blog posts/articles.
- `presentations/`: Directory for Quarto Revealjs presentations.
/
