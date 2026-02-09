# Flashcards (Anki Basic)

This repo contains Anki import files (`.txt`) with **tab-separated** fields for **Basic** notes.

## Format (hard requirements)
- One card per line
- Exactly 2 fields per line: `Front<TAB>Back`
- Delimiter is a **literal tab character** (not spaces, not the text `\t`)
- UTF-8 encoding
- No extra tabs; no embedded newlines inside fields

## Organization
- Content is grouped by topic under numbered subfolders to keep a stable study order (e.g., `rust/01-intro/`).
- Each topic folder contains an `anki.txt`.
- Each topic folder can also contain an `all.txt` that combines all `*/anki.txt` files under that topic (recommended import).

## Import into Anki
- Prefer importing `<topic>/all.txt` (for example, `rust/all.txt`) to import the whole topic at once.
- Note type: **Basic**
- Field separator: **Tab**
