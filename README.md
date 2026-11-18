# Barcode Update System

A standalone React + TypeScript frontend prototype inspired by the supplied Dynamics 365 Business Central screenshots.

## Run locally
1. Install Node.js 20+.
2. In this folder run `npm install`.
3. Run `npm run dev`.
4. Open the local URL printed by Vite.

## Included interactions
- Barcode / item lookup popup with search and selection.
- General fields and batch lines.
- Update and clear confirmation dialogs.
- Add/remove batch rows.
- Barcode label preview and browser print.
- Responsive layout for desktop and smaller screens.

## Important
This is a frontend prototype with sample data. Update, clear and lookup actions currently operate locally in the browser; no ERP connection, authentication, database, or live barcode API is configured. Connect a backend/API and replace the sample records before production use.