# Self Log Portfolio

A single-page personal portfolio for Fayas P Sulfikkar built with plain HTML, CSS, and JavaScript. The site uses a system-log visual language, animated timeline storytelling, and a terminal-inspired interaction model.

## Overview

This repository contains a static portfolio experience centered around:

- a cinematic hero section
- an event-log timeline with modal detail views
- a custom cursor and scroll progress treatment
- responsive layouts tuned for desktop, tablet, and mobile
- a lightweight setup with no frontend framework

## Stack

- HTML
- CSS
- JavaScript
- Google Fonts

## Local Development

Start a local server from the project root:

```bash
npm run dev
```

Then open:

```text
http://localhost:8000
```

You can also use:

```bash
npm run serve
```

## Project Structure

```text
.
├── .editorconfig
├── .github/
│   └── workflows/
│       └── pages.yml
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── index.html
└── package.json
```

## Key Features

- Terminal-inspired visual identity with a narrative portfolio layout
- Scroll-based reveal animations using Intersection Observer
- Interactive timeline cards backed by a modal content data structure
- Fully responsive behavior for smaller screens
- Static deployment compatibility, including GitHub Pages

## Editing Guide

The site content is primarily maintained in [index.html](index.html):

- hero copy is defined in the hero section markup
- timeline cards are defined in the timeline section markup
- modal timeline content is driven by the `D` array in the script block
- terminal panel text is configured in the `terminalContent` object

## Deployment

The repository includes a GitHub Actions workflow for GitHub Pages deployment in [.github/workflows/pages.yml](.github/workflows/pages.yml).

To use it:

1. Push the repository to GitHub.
2. In the repository settings, enable GitHub Pages with GitHub Actions as the source.
3. Push to `main` to trigger deployment.

## Quality Notes

This project intentionally keeps the implementation simple and portable:

- no build step
- no framework lock-in
- easy local preview with a static server
- straightforward hosting on GitHub Pages or any static host

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
