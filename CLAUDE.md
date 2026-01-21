# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal portfolio website for Victor G. Jorge (Business Operations professional). Static HTML/CSS site hosted on GitHub Pages.

## Development

No build process. Open `index.html` directly in a browser to preview. Push to `main` branch to deploy via GitHub Pages.

## Architecture

- **index.html** - Main portfolio page with all sections (hero, case studies grid, skills, about, references, contact)
- **case-*.html** - Individual case study pages with accordion-style expandable sections
- **styles.css** - Complete styling with CSS variables and responsive breakpoints

### Assets Structure

```
assets/
└── images/
    ├── profile.jpeg          # Main profile photo
    ├── logos/                 # Company logos for case studies
    ├── references/            # Reference contact photos
    ├── case-studies/          # Screenshots and visuals for case studies
    └── unused/                # Archived/alternate images
```

**Naming convention**: Use kebab-case for all asset filenames (e.g., `joe-fernandez.png`, not `Joe Fernandez.png`).

### CSS Design System

Color variables defined in `:root`:
- `--primary`: Purple (#7a00df)
- `--accent`: Cyan (#00d4ff)
- `--accent-warm`: Orange (#ff6b35)
- `--bg-*`: Dark background variants

### JavaScript

Minimal vanilla JS for accordion toggles on case study pages. No framework dependencies.

## Content Guidelines

- Professional tone focused on business operations, data analytics, and process improvement
- Case studies follow consistent structure: Overview, Problem, Approach, Results
- References section includes real professional contacts with photos
