# CLAUDE.md

## Project Overview
Personal website for Alex Lutz. Simple, clean portfolio page hosted on GitHub Pages at alexinslc.com.

## Tech Stack
- **Frontend:** HTML5, Tailwind CSS (CDN), vanilla JS
- **Hosting:** GitHub Pages with custom CNAME

## Files
- `index.html` - Main (only) page
- `CNAME` - Custom domain config
- `site.webmanifest` - PWA manifest
- Various favicon/icon assets

## Development
No build step. Edit `index.html` directly and push.

```bash
# Local preview
python3 -m http.server 8000
# Then open http://localhost:8000
```

## Deployment
Push to `main` branch → GitHub Pages auto-deploys.

## Style Notes
- Minimalist aesthetic
- Dark mode default
- Mobile-first responsive
- Clean typography with system fonts via Tailwind
