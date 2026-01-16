# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the documentation site for Hackerspace.gent (0x20), built with MkDocs Material and hosted on GitHub Pages at https://docs.hackerspace.gent.

## Commands

```bash
# Install dependencies
pip install -r requirements.txt

# Run local dev server (http://127.0.0.1:8000/)
mkdocs serve

# Build static site
mkdocs build

# Deploy to GitHub Pages (automated via CI on push to main)
mkdocs gh-deploy --force --clean --verbose
```

## Architecture

- **docs/**: All markdown content lives here
- **docs/infra/**: Infrastructure documentation pages
- **docs/infra/images/**: Images for infrastructure docs
- **docs/assets/**: Site-wide assets (logo, favicon)
- **mkdocs.yml**: Site configuration including navigation structure

## Adding Content

- New pages must be added to the `nav` section in `mkdocs.yml` to appear in navigation
- Images should go in an `images/` folder alongside the markdown file
- Optimize images for web before adding (not raw photos)
- Uses GLightbox plugin for image lightboxes
- Full formatting options: https://squidfunk.github.io/mkdocs-material/reference/
