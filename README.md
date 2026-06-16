# Frank — Developer Portfolio

A self-contained contractor portfolio you can open in VS Code, edit, and deploy anywhere.

## What's in here

| File | What it is |
|------|------------|
| `index.html` | The portfolio page. Single file — all CSS and JS are inline, no build step. |
| `pitch.md` | Copy-paste pitch in three lengths for proposals, DMs, and cold email. |
| `CLAUDE.md` | Context for Claude Code if you later want to rebuild this as a Next.js app. |
| `README.md` | This file. |

## Preview it in VS Code

1. Open this folder in VS Code (`File → Open Folder`).
2. Easiest: install the **Live Server** extension, right-click `index.html`, "Open with Live Server."
3. Or just double-click `index.html` to open it in your browser. No server needed.
4. Or from the terminal: `npx serve .` then open the printed URL.

## Before you publish — edit these

The page is populated with your real projects, but a few things are placeholders:

- **Email** — search `your-email@example.com` in `index.html` and replace it.
- **GitHub link** — the "View GitHub" button href is `#`. Point it at your profile.
- **Project links** — the live links go to `michael-rust.vercel.app` and `authors-codex.vercel.app`. Confirm those still resolve, and turn any "Case study on request" cards into real links if those projects are public.
- **Surname / contact** — the wordmark is just "FRANK." Add a surname or contact line if you want.

## Deploy it (all free, all static)

- **Vercel** — `npx vercel` in this folder, or drag it into the Vercel dashboard. (You already use Vercel.)
- **Netlify** — drag the folder onto app.netlify.com/drop.
- **GitHub Pages** — push to a repo, enable Pages on the main branch.

## Design notes

The look is an "instrument-maker's workbench" — deep ink base, restrained brass accents, Cormorant Garamond + IBM Plex. It nods to your codex/esoteric brand without going full mystical, since the audience here is founders who want clean AI apps shipped. The signature detail is the framed corner-ticks on each project card (a precision-instrument framing). Fonts load from Google Fonts; everything else is self-contained.
