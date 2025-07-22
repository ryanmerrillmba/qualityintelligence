# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Quality Intelligence (qualityintelligence.co), a Business Intelligence as a Service company. The site is hosted on Cloudflare Pages and deployed from GitHub.

## Development Commands

This is a static HTML/CSS/JavaScript website with no build process. Files are served directly.

### Local Development
- Use any local HTTP server to preview changes:
  - `python -m http.server 8000` (Python)
  - `npx serve .` (Node.js)
  - Live Server extension in VS Code

### Deployment
- Push changes to GitHub main branch
- Cloudflare Pages automatically deploys from GitHub
- Custom domain: qualityintelligence.co

## Project Structure

```
/
├── index.html              # Main landing page
├── pricing.html            # Pricing page
├── Images/                 # Logo and image assets
│   └── IMG_4682.JPG       # Quality Intelligence logo
├── Documents/             # Design documentation and specs
└── assets/               # CSS, JS, and other static assets
```

## Brand Guidelines

### Logo
- Primary logo: `Images/IMG_4682.JPG` - Navy blue 3D "Q" design
- Logo should be optimized for web (create PNG/SVG variants)
- Use as favicon and primary brand element

### Color Scheme
- Primary: Navy blue (matching logo gradient)
- Secondary: Lighter blues, whites, grays
- Professional BI/analytics color palette

### Content Strategy
- Focus: Business Intelligence as a Service
- Target audience: Enterprise clients needing BI solutions
- Tone: Professional, data-driven, trustworthy

## Technical Notes

- Uses TailwindCSS via CDN for styling
- Responsive design for mobile/tablet/desktop
- No backend or database required
- All content is static HTML/CSS/JS

## Content Consistency

Ensure all pages use "Quality Intelligence" branding consistently (not "DataWise" or other variants found in legacy files).