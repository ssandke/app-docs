# Sandke Apps Site

Public-facing support and privacy site for Sandke mobile apps.

This repository is intended for static hosting on GitHub Pages with the custom domain `apps.sandke.com`.

## Purpose

Each app gets stable public URLs for:

- app landing page
- support page
- privacy policy

Example URLs for Point Me At It:

- `https://apps.sandke.com/pointmeatit/`
- `https://apps.sandke.com/pointmeatit/support/`
- `https://apps.sandke.com/pointmeatit/privacy/`

## Repo Layout

```text
.
├── CNAME
├── index.html
├── styles.css
├── pointmeatit/
│   ├── index.html
│   ├── support/
│   │   └── index.html
│   └── privacy/
│       └── index.html
└── README.md

