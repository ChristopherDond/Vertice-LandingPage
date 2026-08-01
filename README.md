# Vértice Landing Page

[Versão em português](README.pt-BR.md)

Institutional landing page for Vértice — official version built with **Next.js** (static export).

## About

Vértice connects those who *do* with those who *know how to manage* — with simple language, safety, and support to grow.
This is the official landing page with the project's real content: manifesto, informal entrepreneur barriers,
platform pillars, Violet Protocol, business model, and impact (SDGs).

## Page content

- Hero with manifesto "Where talent meets management" + statistics
- Marquee with platform pillars
- Problem (3 barriers) and Objective/Manifesto
- How it works (4 steps: signup → shield track → match → escrow)
- Pillars: Provide/Request Service · Violet Protocol · Strategic Partners
- Violet Protocol with phases v1–v3
- Who it's for (3 personas) and Business model
- Impact (SDG 1, 5, 8, 10, 17)
- Final vision/CTA + contacts

## Structure

- `index.html` — generated static page (Next.js export)
- `_next/` — static assets (JS/CSS)
- `logo-vertice.png` — brand
- `404.html` — error page

## Source code

The source code (Next.js + React + Tailwind + Three.js) lives in the `VerticeWeb-v0` project.
This folder contains only the published static build.

## How to update

1. In the `VerticeWeb-v0` project: `npm run build`
2. Copy the contents of `out/` to this folder
3. Commit and push

## Visual direction

Elegant dark theme, editorial typography (Playfair Display + Inter), violet/pink accents,
handcrafted 3D mesh in the hero (Three.js), purposeful micro-interactions (magnetic buttons, 3D tilt, reveal).
