---
hide:
  - navigation
  - toc
---

# Home

This is an example of using MkDocs with the Material theme to publish to GitHub
Pages, and also use repository wikis as submodules to combine team-driven
documentation.

## MkDocs Configuration

Barebones, with two additional plugins:

* https://pypi.org/project/mkdocs-same-dir/ for not requiring a `docs/` folder
* https://pypi.org/project/mkdocs-callouts/ for converting GitHub Wiki "alert" formatting into MkDocs Material Admonitions

## GitHub Actions

Uses the [Deploy MkDocs marketplace action](https://github.com/marketplace/actions/deploy-mkdocs) to deploy using the built-in 

## Caveats

These repositories are public on my personal account. Using submodules with private wikis
