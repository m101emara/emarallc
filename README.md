# Emara AI Submission Package

This workspace contains a complete investor-facing package for Cloudflare Pages and program submissions.

## Files Included

- `index.html`: Premium landing page (deploy-ready)
- `architecture.svg`: Visual system architecture diagram
- `pitch-deck.html`: Investor deck source (export to PDF)
- `demo-script.md`: 2-3 minute demo narrative + short pitch
- `deck-narration-60s.md`: Slide-by-slide 60-second narration script
- `product-chat.svg`: Mock screenshot (AI assistant)
- `product-formulation.svg`: Mock screenshot (formulation studio)
- `product-qc.svg`: Mock screenshot (QC analytics)

## 1) Deploy Website to Cloudflare Pages

1. Create a GitHub repository.
2. Upload all files from this folder to the repository root.
3. In Cloudflare Pages, click **Create a project**.
4. Connect your GitHub repository.
5. Framework preset: **None**.
6. Build command: leave empty.
7. Build output directory: `/`.
8. Deploy.

The website is static, so no build step is required.

## 2) Export Investor Deck to PDF

1. Open `pitch-deck.html` in Chrome or Edge.
2. Press `Ctrl+P`.
3. Destination: **Save as PDF**.
4. Enable **Background graphics**.
5. Paper size: A4 or Letter.
6. Margins: Default.
7. Save as `emara-investor-deck.pdf`.

## 3) Submission Tips

Use this positioning consistently:

> Emara AI is a scalable cloud platform designed to serve multiple manufacturers through an industrial AI architecture.

Suggested links to submit:

- Cloudflare Pages URL (website)
- PDF deck URL (Google Drive or Notion)
- Optional architecture image URL (`architecture.svg` rendered in browser)
- Optional product visuals (`product-chat.svg`, `product-formulation.svg`, `product-qc.svg`)

## 4) Optional Final Upgrades

- Replace placeholder metrics with real pilot metrics
- Add your team slide to `pitch-deck.html`
- Add a 60-second demo video link on `index.html`
