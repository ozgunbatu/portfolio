# Batuhan Dogan Portfolio

## Overview
A static HTML portfolio website showcasing analytics, product thinking, and UX strategy case studies. Built with plain HTML and Tailwind CSS (via CDN).

## Project Structure
```
.
├── index.html          # Main homepage
├── cases/              # Case study pages
│   ├── checkout-ux.html
│   ├── ev-demand.html
│   ├── seo-growth.html
│   └── ui-redesign.html
├── server.py           # Development server (Python)
└── assets/             # Static assets (CV, images - not yet added)
```

## Development
- Run: `python server.py` (serves on port 5000)
- The server includes cache-control headers to prevent caching issues

## Deployment
- Configured as a static site deployment
- Public directory: `.` (root)

## Features
- Responsive design with Tailwind CSS
- Language toggle (English/German)
- Case study showcase grid
- Contact section

commit:

git add README.md
git commit -m "Trigger GitHub Pages redeploy"
git push origin main

mv replit.md README.md
git add README.md
git commit -m "Rename replid.md to README.md for GitHub portfolio"
git push origin main
