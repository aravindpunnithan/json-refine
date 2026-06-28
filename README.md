# JSON / YAML Formatter & Validator

A fast, fully client-side developer tool for formatting, validating, and converting between **JSON** and **YAML**. No build step, no server — a single `index.html` that runs entirely in your browser and works offline once loaded.

🔗 **Live demo:** https://aravindpunnithan.github.io/json-refine/

## Features

- **Format JSON** and **Format YAML** — prettify pasted input
- **JSON → YAML** and **YAML → JSON** conversion with correct type preservation (numbers, booleans, nulls, nested arrays/objects)
- **Validate** — pass/fail with `Line X, Col Y` error locations
- **Minify** JSON to a single line
- Two-panel layout with line numbers, character/line counts, and syntax highlighting
- Options: indent (2 / 4 / tab), sort keys, auto-detect & format on paste
- Copy-to-clipboard, dark/light theme toggle
- Responsive — panels stack on mobile

## Usage

Open `index.html` in any modern browser, paste your JSON or YAML, and click an action. That's it.

## Tech

Vanilla JavaScript with two CDN libraries:

- [js-yaml](https://github.com/nodeca/js-yaml) — JSON ↔ YAML conversion
- [highlight.js](https://highlightjs.org/) — output syntax highlighting

## License

MIT
