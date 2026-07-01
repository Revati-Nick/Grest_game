# Grest Game — TAPWIN

A tap-to-win game built as a single HTML file, deployed via Vercel.

## How to Run

### Locally

Open `tapwin.html` directly in any browser — no build step or server required:

```bash
open tapwin.html
```

Or serve it with any static file server, e.g.:

```bash
npx serve .
# then visit http://localhost:3000
```

### Deploy to Vercel

```bash
npx vercel
```

The `vercel.json` config rewrites all routes to `tapwin.html`, so the game works at any path on the deployed URL.
