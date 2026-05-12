# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

A personal German-language recipe collection stored as Markdown files. Each recipe is a standalone `.md` file in the root directory. Accompanying photos live in `pictures/`.

## Recipe format conventions

Recipes follow a consistent German-language Markdown structure:

- `# Title` — recipe name (German, with original-language subtitle in parentheses if applicable)
- `## Section` — major parts (e.g. `## Zutaten`, `## Zubereitung`, or named components like `## Hefeteig`)
- `### Zutaten:` / `### Zubereitung:` — ingredient lists and numbered steps within a component
- Quantities use metric units (g, mL, °C); `EL` (Esslöffel) and `TL` (Teelöffel) are acceptable for spoon measures
- Images at the bottom: `![Alt text](pictures/filename.jpg)` — use `<img src="..." width="...">` only when resizing is needed
- Optional `## Danksagung` block at the end to credit the recipe source; omit entirely if there is no one to credit

## Contributing

Per `CONTRIBUTING.md`: only add recipes that are genuinely tasty. Quantities should be as precise as possible. New recipes can be submitted in any format and will be formatted into the standard structure before being added.
