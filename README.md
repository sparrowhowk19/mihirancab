# Mihiran Cabs — Tourism Website

## Deploy to Cloudflare Pages

1. Go to https://pages.cloudflare.com/
2. Click "Create a project" → "Direct Upload"
3. Upload the entire contents of this ZIP (not the ZIP itself)
4. Set build settings:
   - Framework preset: None
   - Build command: (leave empty)
   - Build output directory: /
5. Click Deploy

## File Structure
```
index.html          ← Main website (all CSS & JS inline)
images/             ← All AI-generated images (local)
_headers            ← Cloudflare cache & security headers
_redirects          ← SPA redirect rules
```

## Features
- Full responsive design (mobile/tablet/desktop)
- Dark/Light mode toggle
- Hero slideshow (5 slides, Ken Burns effect)
- Parallax scroll animations
- Glassmorphism effects
- 3D tilt cards
- Fare estimator
- AI chatbot
- Floating action buttons
- Booking form with validation
- Tourist destinations with filter tabs
- Animated counters
- Custom cursor
- PWA-ready

Built with pure HTML, CSS & JavaScript — no dependencies to install.
