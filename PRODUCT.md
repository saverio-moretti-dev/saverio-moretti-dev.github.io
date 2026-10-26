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

- Live multimeter: https://sem-brana-site.vercel.app/plugins/multi-metering/multi-metering.html (single HTML file, Web Audio API, Canvas).
- Public repos: `saverio-moretti-dev/reversibleimport` (PrestaShop 8.1 module, tests), `saverio-moretti-dev/guardaroba` (PWA, Node functions on Vercel).
- Token manager UI screenshots: `~/Desktop/SEM Brana/Brana studio/coding/plugin/claude-token-manager/docs/screenshots/` (desktop/mobile, light/dark).
- Metrics: 183 scripts/apps/flows (≈50 in use), catalog 10k→120k+ products, ~20 modules + 7 fixed, Amazon 12 marketplaces / 239 tests, Danea sync 244 tests, bot study 11.1% real visitors / up to 41.5% PHP time blocked in simulation.
- **Missing, to be provided by the user**: screenshots of audio plugin interfaces, guardaroba phone screenshots (or captured by us from a local run with fake data). Never fabricate.

## Product Principles

1. Show, don't claim: every statement next to its proof (image, demo, number, code, link).
2. Simple at first glance, depth on demand.
3. No generic AI look («ai slop» is the failure the user named first).
4. Professional and competent, impressive through simplicity, also with big, bold solutions where they earn it.

## Accessibility & Inclusion

Readable on phone; real text (not text in images) for key facts; keyboard and screen reader basics.
