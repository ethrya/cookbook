# Readme

## About

This contains a list of rough recipies and cooking information

## How to update

I host this on github pages here: https://ethrya.github.io/cookbook

To publish make updates to pages. To add a new page, add that to `_quarto.yml`.

Site-wide settings (theme, navbar, search, table of contents) live in `_quarto.yml`,
and the kitchen-readability tweaks (fonts, spacing) live in `custom.scss`. Both are
version-controlled.

To preview locally before publishing, run `quarto preview` in terminal. Then run
`quarto publish` and follow the prompts.

### Per-recipe method tabs

Recipes with both a pressure-cooker and stovetop method use a tabset so you can click
between them. The pattern (see Yellow Dal in `curry.qmd`) is:

```markdown
### Steps

::: {.panel-tabset}

## Pressure cooker
1. ...

## Stovetop
1. ...

:::
```
