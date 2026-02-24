# Backyard Movie Night

> A promotional website for a backyard movie night rental service in the Greater Toronto Area, featuring booking information, pricing, image gallery, and optional add-ons.

![Status](https://img.shields.io/badge/status-archived-lightgrey)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Live Demo

[https://izzydoesizzy.github.io/itsmovienight](https://izzydoesizzy.github.io/itsmovienight)

## Overview

"Backyard Movie Night" is a commercial landing page for a GTA-based outdoor movie rental service launched during the COVID-19 pandemic. The service provided a safe, socially distanced entertainment option, delivering a 100-inch popup screen, HD projector, and Bose speakers to customers' backyards. Visitors can browse the equipment offering, view a photo gallery of past events, see pricing, explore optional add-ons (game console rental, snack bars, Wi-Fi extenders), and book directly via phone, email, or Calendly.

## Features

- Revolution Slider hero section with typewriter animation effect cycling through "With your Friends" / "With Your Family"
- Responsive navigation with sticky header and mobile hamburger menu
- Equipment showcase: 100-inch screen, HD projector, Bose speakers, media connectivity (Netflix, PS4, Xbox, Switch)
- Full-width image gallery with Isotope grid layout and Magnific Popup lightbox
- Pricing section with call-for-quote and direct contact buttons
- Optional add-ons section: game console rental, snack bar, Wi-Fi extender
- Bootstrap 4 responsive grid layout
- Google Analytics integration
- Archive pages and additional gallery/pricing table templates
- CNAME configured for custom domain (itsmovienight.ca)

## Screenshots

<!-- ![Screenshot](screenshot.png) -->

## Tech Stack

- HTML5
- CSS3 (Bootstrap 4, custom theme, corporate skin)
- jQuery
- Revolution Slider (hero carousel with typewriter addon)
- Owl Carousel
- Isotope (masonry grid)
- Magnific Popup (lightbox)
- Animate.css
- Font Awesome & Simple Line Icons
- Google Analytics
- Hosted on GitHub Pages

## Getting Started

### Run Locally

No build step required:

1. **Clone the repository**
   ```bash
   git clone https://github.com/izzydoesizzy/itsmovienight.git
   cd itsmovienight
   ```

2. **Open in browser**
   ```bash
   open index.html
   # or use a local server:
   npx serve .
   ```

### Deploy to GitHub Pages

1. Push to the `master` branch
2. Go to Settings > Pages > Source: Deploy from branch
3. Site live at `https://izzydoesizzy.github.io/itsmovienight`

## Project Structure

```
itsmovienight/
├── index.html                      # Main landing page
├── archive.html                    # Archive page
├── elements-image-gallery.html     # Gallery template
├── elements-pricing-tables.html    # Pricing table template
├── CNAME                           # Custom domain config
├── css/
│   ├── theme.css                   # Main theme styles
│   ├── theme-elements.css          # UI component styles
│   ├── theme-blog.css              # Blog styles
│   ├── theme-shop.css              # Shop styles
│   ├── custom.css                  # Custom overrides
│   └── skins/                      # Corporate skin variants
├── js/
│   ├── theme.js                    # Theme JavaScript
│   ├── custom.js                   # Custom scripts
│   └── theme.init.js               # Theme initialization
├── img/                            # Site images and gallery photos
├── vendor/                         # Third-party libraries (Bootstrap, jQuery, RS Plugin, etc.)
├── ajax/                           # AJAX content
├── php/                            # PHP utilities
├── video/                          # Video assets
├── archive/                        # Archived site versions
└── master/                         # Additional assets
```

## Tags

`fun-project` `curated-list`

## Created

2020-07

## Status

Legacy -- Built as a COVID-era backyard entertainment service site.

## Author

**Izzy Piyale-Sheard** -- [@izzydoesizzy](https://github.com/izzydoesizzy)
