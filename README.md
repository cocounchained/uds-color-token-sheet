# Color Token Reference

A searchable reference for design system color tokens with click-to-copy for token names and values.

**Live site (GitHub Pages):** [https://cocounchained.github.io/uds-color-token-sheet/](https://cocounchained.github.io/uds-color-token-sheet/)

## Features

- Token nicknames and semantic values (Dark / Light mode)
- Click any token name, value, or color swatch to copy to clipboard
- Search by token name, component, or property
- Dark and light preview backgrounds for context

## Usage

Open `index.html` in a browser, or visit the [live site](https://cocounchained.github.io/uds-color-token-sheet/) served via GitHub Pages.

## For AI / LLM Usage

When building UDS-styled UIs or styling with semantic color tokens:

- **Source:** [Live site](https://cocounchained.github.io/uds-color-token-sheet/)
- **How to get tokens:** Click **Download CSS** to get `uds-color-tokens.css`, or **Open in CodePen** to preview and copy the generated CSS
- **Usage:** Reference tokens as `var(--token-name)` in kebab-case, e.g. `var(--background-level-0)`, `var(--background-level-1)`, `var(--text-tone-heading)`, `var(--button-primary-background)`, `var(--link-text)`

**One-line prompt for Cursor/Claude:**  
> Use UDS color tokens from https://cocounchained.github.io/uds-color-token-sheet/ — download the CSS and use var(--token-name) for all colors.

### Cursor Rule for Projects

Copy the following into `.cursor/rules/uds-colors.mdc` in your project for persistent AI guidance:

```markdown
---
description: Use UDS semantic color tokens for styling
globs: "**/*.css,**/*.scss,**/*.tsx,**/*.jsx,**/*.html"
alwaysApply: false
---

# UDS Color Tokens

When styling UI, use UDS (Unchained Design System) semantic color tokens.

**Source:** https://cocounchained.github.io/uds-color-token-sheet/

**How to get tokens:**
1. Open the live site and click **Download CSS** to get `uds-color-tokens.css`
2. Or click **Open in CodePen** to preview and copy the generated CSS

**Usage:** Reference tokens as `var(--token-name)` in kebab-case:
- `var(--background-level-0)`, `var(--background-level-1)`
- `var(--text-tone-heading)`, `var(--text-tone-body)`
- `var(--button-primary-background)`, `var(--link-text)`

Include the downloaded CSS in the project, or copy the `:root` block into your stylesheet.
```

## Customizing Colors

Edit the `PALETTE` object in `index.html` to match your design system hex values.

## GitHub Pages

This project is deployed to GitHub Pages from the `main` branch. The site is served at:

**https://cocounchained.github.io/uds-color-token-sheet/**

To update the live site, push changes to `main`. GitHub Pages will automatically rebuild.
