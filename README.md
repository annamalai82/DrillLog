# DrillLog Pro

**Field drilling data capture and sync for mining & exploration.**

A standalone mobile-first web app for geologists, drillers, and loggers to capture geological, geotechnical, and drilling data on-site — with offline-first design and one-click sync to the main database.

## Features

- **Geological Logging** — Lithology, alteration, weathering, mineralization, structure
- **Geotechnical Logging** — RQD, recovery, hardness, fracture frequency
- **Drill Rig / DDR (PLOD)** — Daily drill reports with full shift tracking
- **Sample Management & Dispatch** — QC samples, batch dispatch to labs
- **Downhole Surveys** — Depth/azimuth/dip with multiple survey methods
- **Visual Strip Log** — Color-coded lithology column
- **Full Audit Trail** — Every action logged with timestamp and user
- **One-Click Sync** — Offline-first, bulk sync to main database
- **Export/Import** — CSV, XLSX, JSON, XML + import assays, pXRF, hyperspectral
- **Light/Dark Mode** — Outdoor and indoor optimized themes
- **Data Validation** — Lookup-table driven with depth overlap checks

## Deploy to Vercel

### Option 1: Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# From the project root
cd drilllog-pro
npm install
vercel
```

### Option 2: GitHub → Vercel

1. Push this folder to a GitHub repo
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the repo
4. Vercel auto-detects Vite — click **Deploy**

### Option 3: Manual Build + Deploy

```bash
npm install
npm run build
vercel deploy --prebuilt
```

## Local Development

```bash
npm install
npm run dev
```

Opens at `http://localhost:5173`

## Tech Stack

- **React 18** + **Vite 6**
- Zero external UI dependencies (pure inline styles)
- Mobile-first responsive design (max-width: 480px)
- Offline-first architecture ready for service worker integration
