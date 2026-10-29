# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS/JS, no build step, served by GitHub Pages from this repo (`saverio-moretti-dev/saverio-moretti-dev.github.io`). Existing choice, kept.

## Users

Two readers arriving from the link in Saverio's CV (Italian job market, e-commerce / automation / AI-solutions roles):
- **Owner or HR, non-technical**: decides in under a minute whether to call. Needs to see what he builds and that it works.
- **Technical lead or developer**: checks method, code, choices, verification.
Order of the page: the non-technical reader is served first, details for the technical reader below. (User, 26/10, D18.)

## Product Purpose

Show what the CV cannot: real artifacts, images, live demos, code, diagrams, how he works and verifies. Success = the reader understands, without being told, that he is very good. «Non devo dire che sono il migliore ma far vedere e capire che sono il migliore.»

## Positioning

A self-taught developer (physics studies, not concluded) who builds the missing tools himself, with Claude Code as main code writer and himself as designer of logic and verifier, and who measures before acting (bot traffic study, 239/244 tests, native-vs-mine identical import). Personal projects show the same habit: a problem at home becomes a working app (guardaroba), a music need becomes a studio analyzer in one HTML file (multimeter), audio plugins in C++.

## Operating Context

Read on phone (from a CV PDF or email) and on desktop. Italian language. Linked from CV under a dedicated «Portfolio» section.

## Capabilities and Constraints

- **No screenshots of company modules** (user, D18). Company work is shown only through text, metrics, diagrams drawn here, and the public rewrite `reversibleimport`.
- Company stays anonymous («azienda di informatica nuova e ricondizionata»); nothing that identifies it.
- Facts must match the CV (`~/Desktop/carriera/cv/cv-ruolo.md`); technical claims verified in code before writing.
- Long is fine, but not one long wall of text: chunked, image-led, scannable.

## Evidence on Hand

- Multimeter: in the page a square demo video `demo/multimeter.mp4` (autoplay muted loop, from the user's `mm.mp4`, 2026-10-29); the real app `demo/multimeter.html` (track `demo/audio/in-my-head.mp3`) opens only via «Apri a schermo intero», meant for desktop. The scaled live iframe + tutorial was removed: on phones it was tiny and unusable.
- Public repos: `saverio-moretti-dev/reversibleimport` (PrestaShop 8.1 module, tests), `saverio-moretti-dev/guardaroba` (PWA, Node functions on Vercel).
- Token manager UI screenshots: `~/Desktop/SEM Brana/Brana studio/coding/plugin/claude-token-manager/docs/screenshots/` (desktop/mobile, light/dark).
- Metrics: 183 scripts/apps/flows (≈50 in use), catalog 10k→120k+ products, ~20 modules + 7 fixed, Amazon 12 marketplaces / 239 tests, Danea sync 244 tests, bot study 11.1% real visitors / up to 41.5% PHP time blocked in simulation.
- Plugin images `img/plugin-*.webp` and guardaroba screenshots `img/guardaroba-*.webp` provided by the user (6769 excluded: shows the Vinted profile URL). Never fabricate.

## Design (26/10, direction «B Banco» + «C» switch)

Dark only, accent `#62c7bf`, Bricolage Grotesque + JetBrains Mono (ligatures off in code). Top bar switch «In breve / Tecnico» (`html.tech`, `.t-only`). First view = work (4 cases: code, SVG diagrams, numbers); personal workshop below (plugins, multimeter, guardaroba, agents) in galleries with arrows, no written instructions. The page is called «sito», never «portfolio». Old «Manuale d'officina» kept in `archivio/officina/`.

## Product Principles

1. Show, don't claim: every statement next to its proof (image, demo, number, code, link).
2. Simple at first glance, depth on demand.
3. No generic AI look («ai slop» is the failure the user named first).
4. Professional and competent, impressive through simplicity, also with big, bold solutions where they earn it.

## Accessibility & Inclusion

Readable on phone; real text (not text in images) for key facts; keyboard and screen reader basics.
