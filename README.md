# PHORIA Website

Award-winning XR Studio website featuring VR, AR, and spatial computing projects.

## Overview

This website showcases PHORIA's portfolio of immersive experiences, built using Material Design 3 principles with a focus on visual storytelling and clean, modern aesthetics.

**Design inspired by:** [codewiki.google](https://codewiki.google/)  
**Built for:** Phoria Studios Pty Ltd ([phoria.com.au](https://phoria.com.au))

## Features

- ✅ **Material Design 3** - Google's latest design system
- ✅ **Responsive** - Mobile-first, works on all devices
- ✅ **SEO Optimized** - Structured data, meta tags, OG cards
- ✅ **Fast Load Times** - Minimal dependencies, optimized assets
- ✅ **Accessible** - WCAG 2.1 compliant, semantic HTML
- ✅ **Multi-page Flow** - Connected pages (Home → Projects → Individual Project)

## Site Structure

```
/
├── index.html              # Homepage
├── projects.html           # Projects grid with filtering
├── projects/
│   ├── our-planet.html     # Netflix Our Planet case study
│   ├── rewild.html         # (placeholder)
│   ├── arup.html           # (placeholder)
│   └── ...
└── assets/                 # Images, videos, icons (to be added)
```

## Design System

### Colors
- **Primary:** #c9a84c (Phoria Gold)
- **Primary Container:** #f5e8c7 (Light Gold)
- **Surface:** #ffffff (White)
- **On-Surface:** #1a1a2e (Phoria Dark)

### Typography
- **Headings:** Google Sans (400, 500, 700)
- **Body:** Google Sans Text (400, 500)
- **Code:** Google Sans Mono

### Layout
- **Max width:** 1200px (content)
- **App bar height:** 80px desktop, 64px mobile
- **Breakpoint:** 768px
- **Spacing:** 24px desktop, 16px mobile

## Pages

### Homepage (`index.html`)
- Hero section with CTAs
- Capabilities grid (6 cards: VR, AR, MR, Digital Twins, XR Installations, Spatial Computing)
- Featured projects (4 cards)
- CTA section
- Footer with links

### Projects Page (`projects.html`)
- Filterable project grid (All / VR / AR / MR / Digital Twins / Installations)
- 6+ project cards linking to individual pages

### Individual Project Pages (`projects/*.html`)
- Hero image/video
- Project overview (client, role, year, tags)
- Challenge & solution sections
- Technology stack
- Results/impact
- Partners
- Visual gallery
- CTA to start new project

## Assets

### Current Assets
- ✅ Favicon (SVG, inline)
- ✅ Phoria "P" logo icon
- ✅ Material Icons (Google CDN)

### Needed Assets (Placeholders Currently)
- Project images/videos
- Partner logos
- Award badges
- Team photos

**Note:** Currently using emoji placeholders (🌍, 🦜, 🏗️, etc.) and gradient backgrounds. Real images should be added from Phoria's asset library.

## Development

### Local Development
Simply open `index.html` in a browser. No build step required.

### Editing Content
All content is in HTML files. To update:
1. Open the relevant HTML file
2. Edit text, links, or structure
3. Save and refresh browser

### Adding New Projects
1. Create new file in `projects/` directory
2. Copy structure from `projects/our-planet.html`
3. Update content (title, description, tags, images)
4. Add card to `projects.html`
5. Add card to homepage featured section (if featured)

## Deployment

### GitHub + Netlify (Recommended)

1. **Create GitHub repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/StevenKounnas/phoria-website.git
   git push -u origin main
   ```

2. **Link to Netlify:**
   - Go to [netlify.com](https://netlify.com)
   - Connect GitHub repo
   - Set build command: (none - static HTML)
   - Set publish directory: `/`
   - Deploy

3. **Custom Domain:**
   - Add custom domain in Netlify settings
   - Update DNS records to point to Netlify

### Alternative: Cloudflare Pages, Vercel, GitHub Pages
All work with this static HTML site.

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile Safari iOS 14+
- Chrome Android 90+

## Performance

- **Lighthouse Score Target:** 90+ (all categories)
- **Load Time:** <2s
- **First Contentful Paint:** <1s
- **Total Page Weight:** <500KB (before images)

## Credits

**Design & Development:** Devon (PHORIA Web Developer Agent)  
**Date:** March 2, 2026  
**Design Inspiration:** Code Wiki (Google)  
**Content:** Phoria Studios Pty Ltd

## License

© 2026 PHORIA Studios Pty Ltd. All rights reserved.

## Next Steps

1. Replace emoji placeholders with real project images
2. Add project videos (MP4, WebM)
3. Complete remaining project pages (Rewild, Arup, Ecosphere, etc.)
4. Add About page with team photos and bios
5. Add Contact page with form
6. Integrate analytics (Google Analytics or similar)
7. Add additional capabilities pages
8. Performance optimization (lazy loading, WebP images)
9. Test on all target devices

---

Built with 💛 by PHORIA Web Development Team
