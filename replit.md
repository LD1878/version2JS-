# JURO Spain Jekyll Site

## Overview
A professional Jekyll-based website for JURO Spain legal services, featuring a comprehensive SCSS design system created with UX best practices in mind.

## Project Structure
```
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page templates
│   └── default.html     # Main layout
├── _includes/           # Reusable components
│   ├── head.html        # Document head
│   ├── header.html      # Site navigation
│   └── footer.html      # Site footer
├── _sass/               # SCSS partials
│   ├── _variables.scss  # Design tokens (colors, spacing, typography)
│   ├── _mixins.scss     # Reusable SCSS patterns
│   ├── _base.scss       # Reset and base typography
│   ├── _layout.scss     # Grid and layout utilities
│   ├── _header.scss     # Navigation styles
│   ├── _hero.scss       # Hero section
│   ├── _buttons.scss    # Button components
│   ├── _cards.scss      # Card components
│   ├── _forms.scss      # Form elements
│   ├── _footer.scss     # Footer styles
│   ├── _animations.scss # Animations and transitions
│   └── _utilities.scss  # Utility classes
├── assets/css/
│   └── main.scss        # Main stylesheet (imports all partials)
├── index.html           # Homepage
├── services.html        # Services page
├── about.html           # About page
└── contact.html         # Contact page
```

## SCSS Architecture
The SCSS follows a modular, scalable architecture:

- **Variables**: Comprehensive design tokens for colors, typography, spacing, shadows, and breakpoints
- **Mixins**: Reusable patterns for media queries, flexbox, focus states, transitions
- **Components**: Standalone, reusable UI components (buttons, cards, forms)
- **Utilities**: Single-purpose helper classes

## Key UX Features
- Responsive mobile-first design
- Sticky header with glassmorphism effect
- Smooth animations and micro-interactions
- Accessible focus states and skip links
- Professional color scheme (red, gold, cream)
- Touch-friendly mobile navigation
- Back-to-top button
- Scroll-based animations

## Running the Site
```bash
bundle install
bundle exec jekyll serve --host 0.0.0.0 --port 5000 --livereload
```

## Recent Changes
- December 2024: Created professional UX-focused SCSS design system
- Enhanced typography with Inter font
- Added comprehensive component library
- Implemented accessibility improvements

## User Preferences
- Spanish theme colors: Red (#E30613), Gold (#FFD700), Cream (#FFF8F0)
- Professional legal services branding
- Clean, modern UX design
