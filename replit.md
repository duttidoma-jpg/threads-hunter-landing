# Threads Hunter - Landing Page

## Overview

Threads Hunter is a specialized digital marketing agency focused on brand promotion within the Threads social media platform. This is a single-page landing website built to showcase the agency's services and drive conversions through WhatsApp contact. The project is designed as a static, performance-optimized landing page with a dark, minimalist aesthetic that aligns with modern social media design trends.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The project follows a **single-page application (SPA)** approach using vanilla HTML, CSS, and JavaScript without any frameworks or build tools. Key architectural decisions include:

- **Static HTML Structure**: Single `index.html` file containing all page content with semantic HTML5 elements and proper accessibility attributes
- **TailwindCSS via CDN**: Utility-first CSS framework loaded externally to avoid build complexity while maintaining responsive design capabilities
- **Vanilla JavaScript**: Minimal native JavaScript for interactive elements (smooth scrolling, animations) without external libraries
- **Asset Organization**: Dedicated `assets/` folder for images, icons, and media files with optimized file naming conventions

### Styling and Design System
- **Dark Theme**: Black/white color scheme with purple accent (#7C3AED) for CTAs and highlights
- **Typography**: Inter font family from Google Fonts for consistent, modern typography
- **Responsive Design**: Mobile-first approach with breakpoints for tablet and desktop views
- **Performance Optimization**: Lightweight animations using CSS transforms and minimal JavaScript

### Content Structure
The landing page is organized into semantic sections with anchor-based navigation:

1. **Hero Section**: Primary value proposition with main CTA
2. **About Section**: Agency introduction and credibility building
3. **Services Grid**: 4-service offering layout with icons and descriptions
4. **Benefits Section**: Competitive advantages with visual icons
5. **Case Studies**: Social proof through before/after project showcases
6. **Testimonials**: Customer feedback for trust building
7. **Secondary CTA**: Conversion reinforcement banner
8. **Contact Information**: Multiple communication channels
9. **Footer**: Legal and additional links

### User Experience Design
- **Conversion-Focused**: All CTAs direct to WhatsApp for immediate contact
- **Progressive Disclosure**: Information hierarchy designed to guide users through the sales funnel
- **Social Proof Integration**: Case studies and testimonials positioned strategically for maximum impact
- **Mobile-Optimized**: Touch-friendly interface with appropriate spacing and button sizes

## External Dependencies

### CDN Services
- **TailwindCSS**: Latest version via official CDN for utility-based styling
- **Google Fonts**: Inter font family for typography consistency
- **Font loading optimization**: Preconnect and crossorigin attributes for performance

### Third-Party Integrations
- **WhatsApp Business API**: Direct messaging integration via `wa.me/77477302959` links
- **Social Media Platforms**: 
  - Telegram: `@managerixx` for alternative contact
  - Email: `marlenyess17@gmail.com` for formal communications

### Asset Requirements
- **Favicon**: `./assets/favicon.ico` for browser tab identification
- **Open Graph Image**: `./assets/og-image.png` for social media sharing
- **Case Study Images**: Placeholder structure for `./assets/case-*.jpg` files
- **Icon System**: SVG-based icons for services and benefits sections

### SEO and Analytics Infrastructure
- **Meta Tags**: Complete Open Graph and Twitter Card implementation for social sharing
- **Structured Data**: Semantic HTML with proper heading hierarchy and alt attributes
- **Performance Targets**: Lighthouse score optimization (90+ for Performance, SEO, Accessibility)
- **Responsive Images**: Optimized asset delivery for different screen sizes

The architecture prioritizes simplicity, performance, and conversion optimization while maintaining professional presentation standards for a B2B service agency.