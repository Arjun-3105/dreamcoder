# DreamCoder website

This directory contains the bilingual landing page for DreamCoder. It uses React, Vite, and Tailwind CSS. The page shows screenshots from `website/public/assets/` and links to the repository's current README, roadmap, privacy notice, and GitHub Releases.

## Run locally

Use the package manager and lockfile already present in this directory:

```bash
cd website
npm ci
npm run dev
```

The site is a static Vite app. `npm run build` writes its output to `website/dist/`.

The GitHub Releases page is linked as release status, not as a direct installer download. Before changing that wording, confirm that the target Release contains working installer assets for the advertised platforms. Keep claims about provider support, H5 access, platform validation, and key storage aligned with the root README and `PRIVACY.md`.
