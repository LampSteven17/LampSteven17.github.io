# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is Steven Lamp's personal academic website built as a Jekyll GitHub Pages site. The site showcases his work as a Computer Science PhD student at the University of Virginia, with a focus on cybersecurity and user emulation techniques.

## Architecture

### Jekyll Structure
- **_config.yml**: Jekyll configuration with site metadata, color scheme, and social links
- **_layouts/default.html**: Main page layout that includes all section components
- **_includes/**: Modular HTML components that make up different sections of the single-page site:
  - `header.html`: Hero section
  - `about.html`: About section
  - `announcments.html`: Announcements section
  - `edexp.html`: Education/Experience section
  - `docs.html`: Documentation/Projects section
  - `contact.html`: Contact information
  - `windows11OpenstackInstallGuide.html`: Technical guide content
  - `nav.html`, `footer.html`, `head.html`, `js.html`: Navigation, footer, and asset includes

### Static Assets
- **css/**: Contains font-awesome icons directory
- **js/**: Bootstrap, jQuery, and theme JavaScript files
- **img/**: Image assets
- **style.css**: Custom styles (currently minimal)

### Content Pages
- **index.html**: Main landing page using default layout
- **win11-openstack-guide.html**: Dedicated page for Windows 11 OpenStack guide

## Development

### Local Development
Since this is a Jekyll site hosted on GitHub Pages, local development requires Jekyll:
```bash
bundle exec jekyll serve
```

### Deployment
The site is automatically deployed via GitHub Pages when changes are pushed to the main branch.

### Content Management
- Main content sections are managed through individual include files in `_includes/`
- Site configuration and metadata in `_config.yml`
- The site uses a single-page design with sections loaded via includes

### Theme
Based on the Grayscale Jekyll theme by Jerome Lachaud, which itself is based on the Grayscale Bootstrap theme.