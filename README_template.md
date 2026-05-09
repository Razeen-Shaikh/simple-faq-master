<h1 align="center">Simple FAQ | devChallenges</h1>

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/simple-faq-challenge" target="_blank">Simple FAQ</a> from <a href="https://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://razeen-shaikh.github.io/simple-faq-master/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/Razeen-Shaikh/simple-faq-master">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/simple-faq-challenge">
      Challenge
    </a>
  </h3>
</div>

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Features](#features)
- [Acknowledgements](#acknowledgements)
- [Author](#author)

## Overview

![Screenshot of the Simple FAQ page](./thumbnail.jpg)

A responsive **Frequently Asked Questions** page built to match the devChallenges references in `/design` (desktop ~1350px, tablet ~1024px, mobile ~412px). It includes a hero block, two FAQ sections with semantic lists, styled links, and a footer credit. Background colors swap at **768px** so mobile keeps a white header over a light gray content area, while larger viewports use a light gray hero and white main section.

### What I learned

- Semantic structure (`header`, `main`, `section`, headings, `ol` / `ul`) improves accessibility and keeps the markup easy to read and change.
- **CSS custom properties** centralize colors and fonts so tweaks stay consistent across breakpoints.
- One **mobile-first media query** (`min-width: 768px`) was enough to mirror the different mockups without duplicating HTML.

### Useful resources

- [Simple FAQ challenge](https://devchallenges.io/challenge/simple-faq-challenge) — Official brief and community solutions.
- [MDN — Using media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) — Reference for breakpoint styling.

## Built with

- Semantic HTML5
- CSS custom properties
- Responsive CSS (mobile-first, `min-width` media query)
- [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts)

## Features

- Centered content column with spacing aligned to the design JPGs.
- FAQ blocks: order tracking (numbered list) and return policy (bullets with bold lead-in labels).
- Styled links for “Tracking page”, “Help Center”, and “Return Policy”.
- Favicon from `/resources/favicon.ico`.

This site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Acknowledgements

- [devChallenges.io](https://devchallenges.io/) for the challenge and starter files.
- Design references in the `/design` folder.

## Author

- Website [your-website.com](https://iamrazeen.vercel.app/)
- GitHub [@your-username](https://github.com/Razeen-Shaikh)
