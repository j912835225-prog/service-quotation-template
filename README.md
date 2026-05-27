# Service Quotation Template

A single-file, zero-dependency bilingual (Chinese/English) service quotation template for creative and production teams.

## Features

- Fill in brand name, client, project, and date directly on the page
- Six pre-built service categories: Pre-production, Art & Styling, Shooting Crew, Logistics, Image Post, Video Post
- Price modes: Fixed amount / Actual Cost / TBD / Included / Waived
- Auto-calculated total with non-fixed item count
- Editable notes section
- Export clean PDF via browser print (hides editing UI automatically)
- Fully responsive, mobile-friendly

## Usage

Open `index.html` directly in any modern browser. No server or build step needed.

To export a PDF: click **Export Clean PDF**, then print to PDF in the browser dialog. Disable "Headers and footers" in the print options for a clean output.

## Customization

- Brand name: click the large heading at the top to edit
- Service items: use the `+ Add` buttons under each category
- Notes: click the notes block to edit
- Currency: hardcoded as RMB — change `getCurrencyLabel()` in the script if needed

## License

MIT
