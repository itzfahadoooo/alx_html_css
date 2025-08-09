# Headphones — ALX HTML & CSS Project

**Status:** Starter files created for Task 0. Ready to continue through tasks 1–8.

## Project Overview

Implement, from scratch and without libraries, a responsive and accessible landing page based on the provided Figma design. Follow the project constraints and deliver the required files for each task.

### Requirements (short)
- No external CSS frameworks
- No JavaScript except in Task 8
- Mobile layout at `max-width: 480px`
- Hover/active link color: `#FF6565`
- Button hover: `opacity: 0.9`
- Max content width: `1000px` centered
- Use provided assets and icon font

## Repository layout (directory: `headphones`)

Files created so far:
- `README.md` (this file)
- `0-index.html` — Task 0 (header/hero)
- `0-styles.css` — styles for Task 0

For full project, you'll create (one set per task):
- `0-index.html`, `0-styles.css`
- `1-index.html`, `1-styles.css`
- `2-index.html`, `2-styles.css`
- ...
- `8-index.html`, `8-styles.css`, `8-script.js`

## How to run locally
1. Unzip `images_.zip` into `headphones/images/`.
2. Copy the holberton icon font files into `headphones/fonts/` and follow the demo.
3. Open the required `*-index.html` file in a browser (no build step).

## Task guidance
Each task should be implemented by copying files from the previous step and extending them. Keep a consistent structure and avoid overly-specific selectors.

### CSS best practices
- Start with a small reset (`* { box-sizing: border-box }` and `body { margin: 0 }`).
- Use CSS variables for colors, spacing, font-sizes, and breakpoints.
- Prefer semantic HTML elements (`header`, `nav`, `main`, `section`, `footer`).
- Keep selectors generic and reusable.

## Accessibility checklist
- Use semantic elements.
- `alt` attributes for images.
- `aria-label`/`aria-expanded` for interactive controls (hamburger menu in Task 8).
- Keyboard focus visible for interactive elements.
- Ensure color contrast — adjust text sizes/backgrounds if needed.

## QA & Manual Review
When you're done with a task, request manual QA by creating a brief testing checklist and screenshot of desktop and mobile.

---