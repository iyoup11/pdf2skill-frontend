# pdf2skill-frontend

Standalone frontend repository for `pdf2skill` web UI.

## What this repo contains

- Pure frontend page (`index.html`)
- No backend code
- Calls backend compile endpoint: `POST /api/compile`

## Local run

You can open `index.html` directly, or serve it with any static server.

Example:

```bash
npx serve .
```

Then open the page and set `API Base URL` to your backend domain.

## Deploy to Vercel

1. Import this repo into Vercel.
2. Framework Preset: `Other`.
3. No build step required.
4. Output directory: `.`

If your API is on another domain, configure CORS on backend.
