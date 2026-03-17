# Campus AI Pitch

## Overview
Static HTML pitch page for **Campus AI Suite** — a dedicated Android/iOS app for Indonesian universities. Sales/marketing deliverable shared via WhatsApp link to university decision-makers.

## Purpose
Single-page mobile-first pitch site showcasing the campus AI app suite. Demonstrates value proposition with an interactive phone mockup, feature grid, and clear CTA.

## Tech Stack
| Component | Technology |
|-----------|------------|
| Frontend | Static HTML + CSS + vanilla JS |
| Fonts | DM Sans (body) + JetBrains Mono (labels, numbers) via Google Fonts |
| Icons | Lucide (inline SVGs, monochrome green stroke) |
| Hosting | GitHub Pages |
| Content | English section labels, Bahasa Indonesia body content |

## Architecture
Single `index.html` file with embedded CSS and JS. No build step, no dependencies beyond Google Fonts CDN.

## Page Sections
1. **Hero** — Campus AI Suite badge, 80% stat, app-focused subtitle
2. **The Problem** — 4 pain cards (message flood, repetitive answers, slow response, fragmented channels)
3. **The Solution** — Phone frame mockup with in-app chat UI + bottom nav (Chat AI, Jadwal, Notifikasi, Profil)
4. **App Features** — 2x3 grid (AI Assistant, Smart Jadwal, Push Notifikasi, Grade Tracker, Beasiswa Matcher, Dokumen Request)
5. **How It Works** — 3 steps (docs → customize → download)
6. **Impact** — 4 stat cards
7. **Our Approach** — RAG, multi-tenant, Bahasa Indonesia, cross-platform
8. **CTA** — WhatsApp contact button (for business inquiry)

## Key Patterns
- Mobile-first responsive design (max-width: 480px, 520px on desktop)
- CSS scroll animations with IntersectionObserver
- Phone mockup with animated chat messages (staggered delays)
- Lucide inline SVGs — no CDN dependency for icons
- Dark navy (#0a0e27) + green accent (#25D366) design system

## Commands
```bash
# Local preview
python -m http.server 8080
# Then open http://localhost:8080
```

## Live URL
https://adityonugrohoid.github.io/campus-ai-pitch/

## Related
- Concept doc: `~/projects/brainstorming/concepts/campus-ai-suite.md`
- Backend repo: `~/projects/campus-ai-bot/` (FastAPI + RAG, works independently)
- Business targets: ITATS, Unair, Ubaya, Petra (Surabaya)
- WA CTA links to: +62 812-3037-817
