# Dimension Journey (Dimensionsreise)

🌐 **English** · [Deutsch](README.de.md) · [中文](README.zh-Hant.md)

**Same event – different worlds – new perspectives**

An interactive, animated web page explaining spatial dimensions from 1D to 5D.
A cat, a ball and five worlds: the same event plays out in every dimension –
once as seen by the cat herself, and once as seen by a being from the next
higher dimension.

**➡️ Live page: https://fco-mt.github.io/dimensionsreise/**

## What the page shows

- **Five worlds side by side:** line (1D), plane (2D), space (3D), 4D space and 5D space – the same story runs synchronously in every column.
- **Three selectable events** (under “Settings”):
  - lifting the ball over the obstacle
  - poking a finger through the cat’s world
  - everyday life only (no intervention)
- **Change of perspective:** What does the cat actually see? Always just an image with one dimension less than her world. And what would the higher being see?
- **Controls:** play, pause and reset the animation, adjust speed and timeline with sliders; individual dimensions can be enlarged – handy for a projector in the classroom.
- **Trilingual:** Deutsch · English · 中文 (switchable at the click of a button)

## The principle behind it

> A being from a higher dimension can move objects in a direction that does
> not exist in the lower dimension.

What is impossible in one world (a ball vanishing from a sealed display case)
is perfectly easy one dimension up.

## Technical details

- A single file: [`index.html`](index.html) – no build step, no dependencies (only fonts from Google Fonts)
- Animations in plain JavaScript on HTML canvas
- Responsive (desktop to smartphone), respects `prefers-reduced-motion`
- Hosted via GitHub Pages (branch `main`, folder `/`)

## Self-hosting and customising

The file `index.html` is all you need – just download it and open it locally
in a browser, or put it on any web server. All texts for the three languages
are collected in the `T` object in the script section of the file.

## Author and licence

© 2026 Manfred Sablotny

This work is licensed under a [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) – see [LICENSE](LICENSE). You are free to share and adapt the page (including for your own teaching), as long as the author is credited.

---

*“Sometimes the impossible is just one direction away.”*
