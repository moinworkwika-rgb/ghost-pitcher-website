# Ghost Pitcher Website

This project is now structured as an Astro site.

## Project Structure
- `src/pages/index.astro` — main homepage
- `public/assets/` — image and media assets used by the page
- `package.json` — Astro scripts and dependency
- `astro.config.mjs` — Astro config

## Run Locally

```bash
cd ~/ghost-pitcher-website
npm install
npm run dev
```

Then open the local URL Astro prints in the terminal, usually `http://localhost:4321`.

## Build For Deployment

```bash
cd ~/ghost-pitcher-website
npm install
npm run build
```

Astro will generate the production-ready site in:

```bash
dist/
```

## What To Upload

You have two valid deployment paths:

1. Upload the whole project folder `ghost-pitcher-website/` to a Git provider and connect it to Netlify, Vercel, or Cloudflare Pages.
2. Build locally with `npm run build` and upload only the generated `dist/` folder to any static host.

If you use an Astro-compatible host, the folder to upload/connect is the project root:

```bash
ghost-pitcher-website/
```

If you export a finished static build manually, the folder to upload is:

```bash
ghost-pitcher-website/dist/
```
