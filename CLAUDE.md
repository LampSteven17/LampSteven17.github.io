# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is Incandescent Studios (IcS) professional website built as a Jekyll GitHub Pages site. The site serves as a professional hub for three main areas: Academic Research, Photography, and Music.

## Architecture

### Jekyll Structure
- **_config.yml**: Jekyll configuration with Incandescent Studios branding, deep crimson and black color scheme
- **_layouts/default.html**: Main page layout with professional dark theme
- **_includes/**: Modular HTML components:
  - `head.html`: HTML head with CSS imports and metadata
  - `nav.html`: Horizontal navigation bar with logo and main section links
  - `hero.html`: Minimal hero section with Incandescent Studios logo and IcS subtitle
  - `footer.html`: Simple footer with copyright and social links

### Static Assets
- **css/main.css**: Custom CSS with deep crimson (#B22222) and black theme
- **img/**: Image assets directory

### Content Pages
- **index.html**: Main landing page with hero section
- **academic.html**: Academic research and publications page
- **photography.html**: Photography portfolio and services page
- **music.html**: Music/drumming EPK page

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
Custom professional dark theme with deep crimson red (#B22222) and black color scheme. Clean, modern design focused on showcasing professional work across academic, photography, and music domains.