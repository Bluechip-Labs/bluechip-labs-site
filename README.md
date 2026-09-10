# Bluechip Labs — website

Single-page static site for Bluechip Labs. No build step, no dependencies.

## Files
- `index.html` — the entire site (self-contained: HTML + CSS + a tiny inline script).
- `logo.png` — brand logo (circuit-snowflake "B"). **Add this file** — the header, hero, and favicon all reference it.

## Preview locally
Double-click `index.html`, or serve the folder:
```bash
npx serve .
```

## Deploy (free)
Any static host works. Easiest:

**Vercel**
1. Sign up at https://vercel.com (free Hobby tier).
2. Drag this folder onto the dashboard, or run:
   ```bash
   npm i -g vercel && vercel
   ```
3. Live at a `*.vercel.app` URL instantly. Add a custom domain later under Project → Settings → Domains.

Netlify (drag-and-drop) and Cloudflare Pages also work at $0.

## Contact
The "Email" button uses a `mailto:` link to `bluechiplabs2026@proton.me`.

## Editing
Colors are CSS variables at the top of `index.html` (`:root { ... }`). The accent (`--gold` / `--gold-soft`) is set to the logo's blue.
