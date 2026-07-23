# FoundrMatch

A swipe-based "founder matching" app.

## Setup

```bash
npm install
npm run dev
```

Then open the local URL Vite prints (usually http://localhost:5173).

## Build for production

```bash
npm run build
```

Output goes to `dist/` — deploy that folder to any static host
(Vercel, Netlify, Cloudflare Pages, S3, etc).

## Notes

- Founder photos are embedded as base64 data URIs directly in
  `src/FoundrMatch.jsx` (that's why the file is a few MB) — no
  external image assets needed.
- Single component, no external UI libraries beyond React itself.
