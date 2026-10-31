# LifeCare Medical Laboratory — React + Vite

A React-based final-year-project prototype for a medical laboratory. The UI is split into reusable React components rather than loading the original HTML inside an iframe.

## Features
- Public lab test booking form
- Disease guide with search and category filtering
- First-time administrator setup and staff login
- Patient registration, editing, searching, and deletion
- Lab result entry with reference-range flags
- Printable / Save-as-PDF laboratory report
- Booking management and conversion of bookings into patient records
- Staff management for administrators
- Responsive layout for desktop and mobile
- Browser `localStorage` persistence for demonstration

## Run locally
Install Node.js (LTS), then in this folder run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```
The generated site is in `dist/`.

## Deploy to GitHub Pages / Vercel
- Push this project to a GitHub repository.
- On Vercel, import the repository. Build command: `npm run build`; output directory: `dist`.
- For GitHub Pages, use a Vite-compatible Pages workflow or deploy the `dist` output.

## Important limitations
This is a student/demo prototype. Data is stored in the current browser only; it is not shared between devices and may be lost if browser storage is cleared. Do not enter real patient information. Before real-world use, add a secure backend/database, proper authentication and authorization, audit logging, validation, backups, and privacy/security controls. The demo stores staff passwords in localStorage and is not suitable for production.
