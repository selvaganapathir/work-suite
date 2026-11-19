# WorkSuite

A mobile-friendly, browser-based productivity workspace with Writer, Sheets and Slides.

## Apps
- **Writer:** rich-text editing, headings, lists, links, browser autosave, HTML download and print-to-PDF.
- **Sheets:** editable 30 × 12 grid, arithmetic and cell references, SUM / AVERAGE / MIN / MAX / COUNT formulas, CSV import/export and XLSX import/export.
- **Slides:** editable slide content, add and navigate slides, presentation mode, HTML download and print-to-PDF.

## Run locally
Open `index.html` in a modern browser, or serve the repository with any static web server.

## GitHub Pages
The included Actions workflow deploys the static site on pushes to `main`. Set **Settings → Pages → Build and deployment → Source** to **GitHub Actions** if it is not already selected.

## Storage and privacy
WorkSuite stores work in this browser's localStorage and does not upload documents. Storage is device- and browser-specific. Export important work regularly. Cloud sync, accounts and collaboration are not included yet.

## File compatibility
- Writer: HTML download and print-to-PDF; native DOCX export is not yet included.
- Sheets: CSV and XLSX import/export. XLSX uses SheetJS from a CDN and requires internet access.
- Slides: HTML presentation download and print-to-PDF; native PPTX export is not yet included.

## License
MIT
