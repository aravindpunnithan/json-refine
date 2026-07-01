# JSON / YAML Formatter & Validator

A fast, fully client-side developer tool for formatting, validating, and converting between **JSON** and **YAML**. No build step, no server — a single `index.html` that runs entirely in your browser and works offline once loaded.

🔗 **Live demo:** https://aravindpunnithan.github.io/json-refine/

Three modes via tabs: **Format**, **Diff**, and **Schema**.

## Features

**Format**

- **Format JSON** and **Format YAML** — prettify pasted input
- **JSON → YAML** and **YAML → JSON** conversion with correct type preservation (numbers, booleans, nulls, nested arrays/objects)
- **Validate** — pass/fail with `Line X, Col Y` error locations
- **Minify** JSON to a single line
- **Raw / Tree** output — syntax-highlighted text or a collapsible tree view with expand/collapse all
- Line numbers, character/line counts, syntax highlighting

**Diff**

- Compare two payloads (each may be JSON *or* YAML)
- **Structural** diff — key-by-key added / removed / changed, independent of formatting or key order
- **Text-line** diff — unified line-by-line view of the formatted output
- Swap A ↔ B

**Schema**

- Validate data against a **JSON Schema** (draft-07), powered by Ajv
- Lists each failure with its instance path and message; includes a sample loader

**General**

- Options: indent (2 / 4 / tab), sort keys, auto-detect & format on paste
- Copy-to-clipboard, dark/light theme toggle
- Responsive — panels stack on mobile

## Usage

Open `index.html` in any modern browser, pick a mode, paste your data, and go. No install required.

## Tech

Vanilla JavaScript with three CDN libraries:

- [js-yaml](https://github.com/nodeca/js-yaml) — JSON ↔ YAML conversion
- [highlight.js](https://highlightjs.org/) — output syntax highlighting
- [Ajv](https://ajv.js.org/) — JSON Schema validation

## License

This is free and unencumbered software released into the public domain under [The Unlicense](UNLICENSE).
