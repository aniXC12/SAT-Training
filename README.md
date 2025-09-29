# SAT Digital Practice Lab

Vite + React + Tailwind single-page app that mirrors the **digital SAT** structure:
- Reading & Writing: 2 modules × 32 min × 27 Qs
- Math: 2 modules × 35 min × 22 Qs
- Adaptive module 2 based on module 1 performance (≥70% → harder)
- Practice mode (instant feedback), full-test mode (timed), history in localStorage, JSON export

## Local Dev
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Deploy
- Push to GitHub, then import the repo in **Vercel** or **Netlify**.
- Framework: `Vite` (auto-detected). No environment variables required.

---
**Note**: This is an independent practice tool and is **not affiliated** with the College Board.
