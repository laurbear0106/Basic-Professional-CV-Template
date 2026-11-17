# Basic Professional CV Template

A one-page, print-ready CV template built as a single self-contained HTML file. Open `Basic Professional CV Template.html` in any browser to view, edit, or print it.

## Credits

- **HTML code created with Claude** (Anthropic's AI assistant).
- **CV template** created using examples from [Graduate School CV and Resume Examples, With Notes](https://vincekotchian.com/personal-statements/graduate-school-cv-examples/) (Vince Kotchian) and from my own project.
- **Color codes** inspired by color palettes on Pinterest.

## Features

- **Sections:** Professional Summary (with Relevant Skills), Experience, Projects, Education.
- **Six color schemes**, switchable from the toolbar at the top of the page:

  | Scheme | Colors |
  |---|---|
  | Black Cherry & Cream Vanilla | `#5D0703` / `#EEDCC8` |
  | Celadon & Violet | `#D7E7C3` / `#8C5383` |
  | Steel Blue & Saffron | `#4F7CAC` / `#E8C547` |

  Each pair can be used either way round (text on background, or reversed).
- **Typography:** Libre Caslon Text for the name and section headings; IBM Plex Sans for all other text. Both fonts are embedded in the file, so it looks the same on every computer.
- **Print / Save PDF:** The button prints to US Letter. The toolbar is hidden and the background color is kept.

## Editing

- **Content:** Edit the text inside `<main class="page">` in the HTML file.
- **Text sizes:** Change the five `--size-*` values near the top of the `<style>` block.
- **Default color scheme:** Change `data-theme` on the `<body>` tag (for example, `data-theme="violet-on-celadon"`).

## Fonts and licenses

The embedded fonts are licensed under the SIL Open Font License 1.1. Copies of the licenses are in the `licenses/` folder.

- Libre Caslon Text © 2012 The Libre Caslon Text Project Authors
- IBM Plex Sans © 2017 IBM Corp.
