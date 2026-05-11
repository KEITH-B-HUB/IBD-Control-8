# IBD-Control-8 Questionnaire

Static questionnaire site generated from `questionnaire-spec-template.xlsx`.

## Files

- `index.html`: single-page questionnaire with embedded scoring and PDF generation.
- `styles.css`: responsive clinical styling for the questionnaire.
- `questionnaire-spec-template.xlsx`: source workbook used for the generated content.

## Workbook Assumptions

- The `Responses` sheet is the source of truth for all scores and red/amber/green colours.
- All 8 questions are required.
- The PDF filename is `IBD-Control-8-Summary.pdf`.

## Local Preview

Open `index.html` directly in a browser, or serve the folder with any static file server. The site has no build step and is suitable for GitHub Pages.
