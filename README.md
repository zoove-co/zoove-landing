# Zoove Landing Page

Marketing website for Zoove — currently a minimal "coming soon" teaser
page ahead of full launch.

## What's here

- `index.html` — single-file static page (HTML/CSS/JS inline, no build step)

## Current state

Dark-theme teaser: wordmark, "Coming soon", an email capture form, and
a Mumbai sign-off. No product or service details are shown yet —
intentional, per brand direction, ahead of the real launch site.

## Known limitation

The email signup form only shows an in-browser confirmation right now.
It is **not yet connected to any storage** — submitted emails are not
saved anywhere. Before sharing this link publicly to actually collect
signups, wire the form to a real destination (e.g. a `signups` table
in the Supabase backend once it exists).

## Deployment

Deployed via Vercel, connected to this repository's `main` branch.
Every push to `main` redeploys automatically.

## Roadmap

This repo will grow into the full marketing site (service pages, SEO
content, trainer sign-up) once the core product architecture is
further along. See the shared Drive project folder for architecture
and requirements docs.
