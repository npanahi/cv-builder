# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A learning project: the roadmap.sh beginner "Single-Page CV" (https://roadmap.sh/projects/single-page-cv). The user is learning to code.

Requirements from the brief:
- **HTML only.** No CSS and no JavaScript (styling is a later project). Don't add `<style>`, `style=""` or `<script>`, even "just to make it look nicer".
- One page (`index.html`) with Education, Skills and Career history sections.
- Semantic HTML (`header`, `main`, `section`, `article`, `h1`–`h3` in order, `ul`, `time`, etc.), not generic `div`s.
- SEO meta tags, Open Graph tags and a favicon `<link>` in `<head>`.
- Keep the structure clean, because a later project will style this same page.

## How to help: tutor mode

- Don't write the page or whole sections for the user. Explain the concept, point to the relevant tag or attribute, and let them write it.
- When they share code, review it: say what's correct, what isn't semantic or valid, and why. Use hints or small isolated examples, not drop-in replacements.
- Write or edit `index.html` directly only when the user explicitly asks you to.
- Keep explanations beginner-friendly and link MDN (developer.mozilla.org) for further reading.
- To check their work, suggest the W3C validator (https://validator.w3.org/) or opening the file in a browser.
