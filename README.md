# Tailwind CSS Positioning Assignment

## Description

This project is a simple landing page created using HTML and Tailwind CSS. The purpose of this assignment is to practice Tailwind positioning utilities.

## Positioning Utilities Used

### Sticky

The navigation bar uses the `sticky` class with `top-0`. This keeps the navigation bar visible while scrolling.

### Relative

The CTA button container and dashboard container use the `relative` class. This creates a positioning reference for absolutely positioned child elements.

### Absolute

The two CTA buttons and the floating information cards use `absolute`. Their positions are controlled using `top`, `bottom`, `left`, and `right` utilities relative to their parent container.

### Fixed

The chat button uses `fixed` positioning so it stays at the bottom-right corner of the browser window even when the page scrolls.

## Technologies Used

- HTML5
- Tailwind CSS (CDN)

## How to Run

1. Download the project files.
2. Open `index.html` in any modern web browser.
3. Internet connection is required because Tailwind CSS is loaded from the CDN.

## Files

- `index.html` - Main webpage
- `README.md` - Project documentation

## Learning Outcome

Through this assignment I learned:

- Difference between `relative` and `absolute`
- How `sticky` works
- When to use `fixed`
- How positioning utilities work together in Tailwind CSS