# JURO Spain Jekyll Theme

A modern, visually striking Jekyll theme designed for legal services websites targeting expats. Features warm Spanish-inspired colors, smooth animations, and responsive design.

## Features

- 🎨 Spanish-inspired color palette (cream, burgundy, gold)
- 📱 Fully responsive design
- 🎯 Clean, professional layouts
- 📝 Blog-ready with post templates
- 🔍 SEO optimized
- ⚡ Fast and lightweight
- 🎭 Smooth animations and hover effects

## Installation

1. Copy all files to your Jekyll project root
2. Install dependencies: `bundle install`
3. Run locally: `bundle exec jekyll serve`

## Directory Structure

```
├── _config.yml              # Site configuration
├── _layouts/                # Page templates
│   ├── default.html
│   ├── page.html
│   ├── post.html
│   └── home.html
├── _includes/               # Reusable components
│   ├── header.html
│   ├── footer.html
│   └── head.html
├── assets/
│   └── css/
│       └── main.css         # Styles
├── index.html               # Homepage
├── about.md                 # About page
├── services.md              # Services page
├── blog.html                # Blog listing
├── contact.md               # Contact page
└── _posts/                  # Blog posts
```

## Customization

### Colors

Edit `assets/css/main.css` to change the color scheme:

```css
:root {
  --primary-color: #E30613;      /* Spanish red */
  --accent-color: #FFD700;       /* Gold */
  --bg-color: #FFF8F0;           /* Warm cream */
  --text-color: #333;
  --dark-red: #7C1F1F;
}
```

### Configuration

Edit `_config.yml` to update site information:

```yaml
title: Your Site Name
description: Your site description
url: "https://yoursite.com"
```

## Creating Content

### New Page

Create a markdown file in the root:

```markdown
---
layout: page
title: Page Title
permalink: /page-url/
---

Your content here
```

### New Blog Post

Create a file in `_posts/` with format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "Your Post Title"
date: 2025-11-23
---

Your content here
```

## Features Included

- Collapsible FAQ sections
- Service cards with icons
- Pricing tables
- Call-to-action buttons
- Blog post grid
- Contact forms (ready for backend integration)
- Breadcrumb navigation
- Table of contents for long posts

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Customize as needed for your project!
