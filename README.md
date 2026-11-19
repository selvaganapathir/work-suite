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


## Exam Photo Studio

The Exam Photo Studio prepares image files locally in the browser. It includes photo crop/resize, brightness and contrast, rotation, touch signature drawing, upload of genuine handwritten declarations and fingerprint/thumb scans, and JPG/PNG export with minimum/maximum file-size checks.

### Included official-source presets

- **JEE Main 2027 (NTA):** photo JPG/JPEG 10–200 KB; signature JPG/JPEG 10–100 KB. The bulletin requires a live photo and a recent passport photo with 80% face visibility, ears visible, no mask and white background. It does not specify pixel dimensions for these two uploads.
- **NEET UG 2026 (NTA):** photo JPG/JPEG 10–200 KB; signature 10–100 KB; left/right fingers and thumb impressions 10–200 KB. The bulletin requires a live photo and a white background / 80% face visibility for the photo. It does not specify pixel dimensions for these image uploads.
- **TNPSC Group II / IIA 2026 (Notification 07/2026):** photo 130 × 170 px, 20–50 KB, with candidate name and photography date printed at the bottom; signature 230 × 75 px, 10–20 KB, blue or black ink on white paper. The studio includes the name/date photo strip. TNPSC's notice contains strict source-photo rules; read the notification before use.
- **IBPS CRP 2026–27 (official calendar):** photo JPEG 20–50 KB; signature JPEG 10–20 KB; thumb impression JPEG 20–50 KB; handwritten declaration JPEG 50–100 KB. The calendar does not state pixel dimensions or the full declaration wording. The applicable detailed notification may add requirements; verify it before submitting.

Official references:
- JEE Main 2027 Information Bulletin: https://jeemain.nta.nic.in/information-bulletin/
- NEET UG 2026 Information Bulletin: https://cdnbbsr.s3waas.gov.in/s37bc1ec1d9c3426357e69acd5bf320061/uploads/2026/02/202602231394640855.pdf
- TNPSC Notification 07/2026: https://tnpsc.gov.in/document/english/07_2026%20Dated_11.08.2026%20English%20version.pdf
- IBPS Calendar 2026–27: https://www.ibps.in/wp-content/uploads/IBPS_CALENDAR_2026-27_final.pdf

**Important:** Presets are tied to the cited exam cycle, not permanent universal rules. Always check the current official notification and upload portal. Where the source does not specify pixels, the canvas size shown is only a working crop and is not presented as an official dimension. The studio cannot capture an authority-required live photo, authenticate biometrics, or create a substitute for the candidate's own handwriting. It prepares an image of a real candidate-supplied document.

## License
MIT
