# Barber Shop Visagismo - Landing Page

## Overview

This is a professional, static landing page for a barber shop and men's styling business that specializes in visagismo (facial aesthetics). The project is built entirely with vanilla HTML, CSS, and JavaScript, with no backend dependencies. It's designed to be deployed to static hosting platforms like GitHub Pages or Hostinger.

The landing page targets men aged 20-60 who value aesthetics, confidence, and professionalism. The design emphasizes masculinity, trust, and modernity through a carefully chosen color palette and smooth animations.

## Recent Changes

**November 15, 2025:**
- Created complete landing page structure with all 7 sections (Hero, Sobre Mí, Servicios, Testimonios, Galería, Contacto, CTA Final)
- Implemented responsive design with mobile-first approach and hamburger menu
- Integrated Google Fonts (Montserrat + Roboto) and custom color palette (dark gray, white, petrol blue #1e4a5f, lime green #7ed321)
- Added smooth scroll navigation and Intersection Observer animations
- Generated 8 professional AI images for hero background, gallery, and services sections
- Configured Python HTTP server workflow for local development on port 5000
- Created comprehensive README.md with GitHub Pages deployment instructions
- Added .gitignore for clean repository management

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture

**Technology Stack:**
- Pure HTML5 for semantic structure
- Vanilla CSS3 with CSS custom properties (CSS variables) for theming
- Vanilla JavaScript (ES6+) with no frameworks or build tools
- Google Fonts API for typography (Montserrat for headings, Roboto for body text)

**Design System:**
- CSS custom properties defined in `:root` for consistent theming
- Color palette: Dark grays/blacks, white, petrol blue (#1e4a5f), and lime green accent (#7ed321)
- Responsive design using flexbox and media queries
- Mobile-first approach with hamburger menu navigation

**Component Structure:**
- Single-page application (SPA) layout with anchor-based navigation
- Modular sections: Hero, About, Services, Testimonials, Gallery, Contact
- Reusable CSS classes following BEM-like naming conventions
- Smooth scroll behavior and intersection observer for animations

**JavaScript Functionality:**
- Mobile navigation toggle with animated hamburger menu
- Smooth scrolling to sections with offset for fixed navbar
- Scroll-based navbar styling (background opacity changes)
- Intersection Observer API for scroll-triggered animations (partially implemented)
- Event delegation for navigation links

**Performance Considerations:**
- Preconnect hints for Google Fonts to reduce latency
- Minimal external dependencies (only Google Fonts)
- Optimized for static hosting with no server-side processing
- Images stored locally in `/images` directory

### File Organization

```
/
├── index.html          # Main entry point (must be in root for GitHub Pages)
├── css/
│   └── styles.css      # All styles in single file
├── js/
│   └── main.js         # All JavaScript functionality
├── images/             # Static image assets
└── README.md           # Documentation
```

**Architecture Rationale:**
- Single HTML file approach chosen for simplicity and GitHub Pages compatibility
- All CSS in one file to minimize HTTP requests
- All JavaScript in one file (no bundler needed)
- Static structure allows deployment to any static host without configuration

### Deployment Strategy

**Primary Target: GitHub Pages**
- Requires `index.html` in repository root
- No build step required
- Free hosting for public repositories

**Alternative: Hostinger**
- Supports direct ZIP upload of project files
- Files must be extracted to `public_html` directory
- Can use FTP or file manager for deployment
- Alternative: Build directly in Hostinger using their AI website builder

## External Dependencies

### Third-Party Services

**Google Fonts API:**
- Montserrat font family (weights: 400, 600, 700, 800) for headings
- Roboto font family (weights: 300, 400, 500) for body text
- Loaded via `<link>` tags with preconnect optimization

**Hosting Platforms (Documented):**
- GitHub Pages (primary, free static hosting)
- Hostinger (alternative, paid hosting with domain support)

### No Backend Services

This is a completely static website with:
- No database
- No server-side processing
- No authentication system
- No API endpoints
- No form processing backend (contact forms would need external service integration)

**Future Integration Considerations:**
If dynamic functionality is needed, consider:
- Formspree or similar for contact form submissions
- Google Analytics for visitor tracking
- Social media embed widgets
- WhatsApp Business API for appointment booking