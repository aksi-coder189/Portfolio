# Aakriti Singh — AI / ML Portfolio

A responsive, static-first portfolio built with React, TypeScript, Vite, Framer Motion, and Lucide. The hero's interactive data sphere is drawn on Canvas with a lightweight 3D projection; it does not require WebGL. Project artwork is illustrative and is not presented as an application screenshot.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Publish with GitHub Pages

The included workflow publishes the site whenever code is pushed to `main`.

1. Create a public GitHub repository named `aksi-coder189.github.io`.
2. Push this project to that repository's `main` branch.
3. In the repository, open **Settings → Pages** and select **GitHub Actions** as the source.
4. Open the **Actions** tab and wait for **Deploy portfolio to GitHub Pages** to finish.
5. Visit `https://aksi-coder189.github.io/`.

The Vite base path is `/` for this account-level Pages URL. If you publish from a regular project repository instead, update `base` in `vite.config.ts` to that repository's path (for example `/portfolio/`).

## Edit the portfolio

- Project summaries, scope, repository links, and case-study notes: `src/projects.ts`. The portfolio currently features 14 curated repositories; the Future_ML internship projects are excluded. Forked work is labeled.
- About, skills, navigation, contact, and profile links: `src/App.tsx`.
- Visual system and responsive behavior: `src/styles.css`.
- `public/resume.pdf` is the resume copy used by the site; replace it when your resume changes.
- Category filters, Gmail compose, and a WhatsApp link with a prefilled message are included.
- Replace the page title and description in `index.html` if the portfolio identity changes.

Project artwork is illustrative, not a screenshot. The case studies link to the public repositories and include notes about prototype status and known limitations. The WhatsApp link opens a chat to the phone number in `src/App.tsx` with a short prefilled greeting.
