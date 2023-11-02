# Rendering bug in Astro

This repository demonstrates a rendering bug in Astro.
This bug occurs both when running the app with `npm run dev` or `npm run build`.

## Expected behavior

The app contains a single page which contains a table wrapped inside a div and a paragraph that lives outside this div.
The paragraph should be rendered outside said div.

## Actual behavior

The paragraph is rendered inside the div.
