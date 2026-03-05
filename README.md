# Color Token Reference

A searchable reference for design system color tokens with click-to-copy for token names and values.

## Features

- Token nicknames and semantic values (Dark / Light mode)
- Click any token name, value, or color swatch to copy to clipboard
- Search by token name, component, or property
- Dark and light preview backgrounds for context

## Usage

Open `index.html` in a browser, or visit your GitHub Pages URL once deployed (e.g. `https://YOUR_USERNAME.github.io/color-tokens/`).

## Customizing Colors

Edit the `PALETTE` object in `index.html` to match your design system hex values.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `color-tokens`).
2. Add the remote and push:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/color-tokens.git
   git branch -M main
   git push -u origin main
   ```
3. In the repo: **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** → **/ (root)** → Save.
4. Your site will be live at `https://YOUR_USERNAME.github.io/color-tokens/` (may take a few minutes).
