# LSBUD Insight Persona Engine & Recommendation Matrix

A static GitHub Pages prototype for the first interaction of the future **LSBUD Insight Safe Digging Hub**.

The page combines:

- a free-text persona/intent engine;
- ranked persona matching;
- recommendation previews;
- OneCall dropdown alignment;
- an Excel-style filterable matrix;
- JSON and CSV data files.

## Contents

- `index.html` - self-contained web app.
- `data/personas.json` - structured persona and recommendation data.
- `data/persona-matrix.csv` - Excel-friendly matrix export.

## Deployment

Upload the contents to a new GitHub repository and enable GitHub Pages from the `main` branch root.

Suggested repository name:

```text
LSBUD-Insight-Persona-Matrix
```

Example Pages URL:

```text
https://lsbud-john.github.io/LSBUD-Insight-Persona-Matrix/
```

## Notes

The free-text engine is deterministic and transparent. It uses keywords, intent phrases, service terms and role clues in `personas.json`; no external AI API is required for this prototype.
