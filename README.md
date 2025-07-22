# Quality Intelligence Website

Business Intelligence as a Service company website for qualityintelligence.co

## Project Structure

```
/
├── index.html              # Main landing page
├── pricing.html            # Pricing page
├── Images/                 # Logo and image assets
│   └── IMG_4682.JPG       # Quality Intelligence logo
├── Documents/             # Design documentation
│   └── UI-UX-Design-Document.md
├── CLAUDE.md              # Development guidelines
└── README.md              # This file
```

## Features

- **Responsive Design**: Mobile-first approach using TailwindCSS
- **Modern Branding**: Navy blue professional design with 3D logo
- **Static Site**: No backend dependencies, optimized for CDN hosting
- **Professional Content**: Focus on Business Intelligence services

## Development

This is a static HTML/CSS/JavaScript website with no build process required.

### Local Development
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using VS Code Live Server extension
```

Visit: http://localhost:8000

## Deployment

### Cloudflare Pages
1. Connect this GitHub repository to Cloudflare Pages
2. Set build command to: (none - static site)
3. Set publish directory to: `/` (root)
4. Configure custom domain: qualityintelligence.co

### Manual Deployment
Upload all files to any static hosting provider (Netlify, Vercel, GitHub Pages, etc.)

## Technology Stack

- **HTML5**: Semantic markup
- **TailwindCSS**: Utility-first CSS framework (via CDN)
- **Google Fonts**: Inter font family
- **Material Icons**: Icon library
- **Vanilla JavaScript**: Minimal interactions

## Brand Assets

- **Logo**: Navy blue 3D "Q" design in `Images/IMG_4682.JPG`
- **Colors**: Navy blue primary, professional gradient
- **Typography**: Inter font family
- **Style**: Modern, trustworthy, data-focused

## Content

- **Homepage**: Company overview, features, solutions, CTA
- **Pricing**: Three-tier pricing structure (Essential, Professional, Enterprise)
- **Industry Focus**: Healthcare, Finance & Banking, Manufacturing

## License

All rights reserved - Quality Intelligence