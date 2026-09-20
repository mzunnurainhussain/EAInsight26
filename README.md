# AI Cyber Nexus — Vercel-ready publication site

A polished, dependency-free static microsite based on the **AI Cyber Nexus** white paper.

## Features
- Futuristic AI/cybersecurity visual identity
- Animated hero, orbit system, scanning UI and ticker
- Glassmorphism + neon threat cards
- Cursor glow, subtle 3D card tilt and magnetic buttons on desktop
- Scroll-reveal animation and reading-progress indicator
- Responsive mobile navigation
- Event photography from the source white paper
- Custom 404 page, favicon, web manifest and social card
- No framework and no build step

## Deploy to Vercel

### Dashboard
1. Upload this folder to a GitHub, GitLab or Bitbucket repository.
2. In Vercel select **Add New → Project**.
3. Import the repository.
4. Set **Framework Preset** to **Other**.
5. Leave **Build Command** and **Output Directory** empty.
6. Click **Deploy**.

### Vercel CLI
```bash
npx vercel
```

## Main files
- `index.html` — publication microsite
- `styles.css` — visual design and responsive layout
- `script.js` — navigation, scroll effects, reveal animations and desktop interactions
- `assets/` — event photography, favicon and social image
- `AI-Cyber-Nexus-Whitepaper.docx` — downloadable source paper
- `vercel.json` — Vercel configuration and security headers
