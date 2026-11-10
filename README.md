# Linktree Page with Tailwind CSS

A small, browser-based exercise for building a Linktree-style profile page with Tailwind CSS. The tutorial takes a plain HTML page through layout, profile styling, link buttons, keyboard focus states, and dark mode.

## Project files

- `start-exercise.html` — unstyled starter page.
- `end-solution.html` — completed example, including a shared Tailwind component class for the links.
- `index.html` — the page browsers and static hosts (such as GitHub Pages) open by default. It currently matches `end-solution.html`, and it's the file to edit when you make the page your own.
- [`docs/linktree-tailwind-step-by-step.md`](docs/linktree-tailwind-step-by-step.md) — the eight-step tutorial and styling extensions.

## Get started

No package installation or build step is needed. Open `start-exercise.html` in a browser to see the starter page, then follow the tutorial. The tutorial has you work in `index.html`: copy the starter markup into it (or copy `start-exercise.html` over it) before Step 1. To view the finished example, open `end-solution.html`.

All the styled pages load Tailwind CSS v4 from jsDelivr, so an internet connection is required for the styles to load. The browser CDN is convenient for this exercise; for a production project, use a local Tailwind build instead.

## Solution vs. tutorial

The “Completed solution” section of the tutorial repeats the full class list on every link. `end-solution.html` goes one step further and applies Extension 1 from the tutorial: the shared button styles live in a `.link` class defined with `@apply` in a `<style type="text/tailwindcss">` block, and each link uses `class="link"`. Both versions render the same page.

## Make it yours

In `index.html`, replace “Your Name” in the `<title>` and heading, rewrite the bio, choose an avatar, and update the link URLs and labels. Replace `you@example.com` in the `mailto:` link with your email address. The `#` links are placeholders and should be replaced with real destinations.

To change every button at once, edit the `.link` class in the `<style>` block rather than the individual links.

## Accessibility

The link buttons include visible keyboard focus styles. The avatar uses an empty `alt` attribute because the adjacent heading provides the profile name; if you use an informative image, provide meaningful alternative text.

## Learn more

- [Tailwind CSS documentation](https://tailwindcss.com/docs)
- [Hover, focus, and other states](https://tailwindcss.com/docs/hover-focus-and-other-states)
- [Dark mode](https://tailwindcss.com/docs/dark-mode)
