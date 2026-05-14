# Portfolio

Single-page portfolio website for Jessie, focused on WordPress, WooCommerce, Shopify, frontend, and backend development work.

## Overview

This project is a static HTML portfolio built in a single file.

- Main file: `index.html`
- Styling: embedded in the `<style>` block inside `index.html`
- Interaction: embedded in the `<script>` block inside `index.html`

The page includes:

- Hero section with service summary
- Services section
- Featured projects with category filters
- Process section
- Contact call-to-action

## Run Locally

Because this is a static site, there is no build step or package installation required.

Open `index.html` directly in a browser, or use a local static server if preferred.

Example with VS Code Live Server:

1. Open the project folder in VS Code.
2. Open `index.html`.
3. Start Live Server.

## Editing Content

Most content updates can be made directly in `index.html`:

- Hero text and profile summary
- Services content
- Project cards
- Contact email link

To update the projects section, edit the `<article class="project-card">` blocks in `index.html`.

## Notes

- The portfolio currently uses client-side project filtering with vanilla JavaScript.
- The footer year updates automatically in the browser.
- This project does not use a framework, bundler, or external dependencies.
