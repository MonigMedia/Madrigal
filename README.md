# Madrigal.mx

Welcome to the Madrigal.mx website repository.

## Project Structure

```
Madrigal/
├── index.html          # Main homepage
├── 404.html            # Custom 404 error page
├── CNAME               # GitHub Pages custom domain
├── robots.txt          # Search engine crawling rules
├── sitemap.xml         # XML sitemap for SEO
├── assets/
│   ├── css/
│   │   └── styles.css  # Main stylesheet
│   ├── js/
│   │   └── main.js     # Main JavaScript
│   └── images/
│       ├── favicon.svg # SVG favicon
│       └── ...         # Other images
└── README.md           # This file
```

## Features

- ✅ Modern, responsive design
- ✅ Dark mode support (auto-detects system preference)
- ✅ SEO optimized with meta tags & structured data
- ✅ Custom 404 error page
- ✅ Accessible (ARIA labels, semantic HTML)
- ✅ Fast loading (minimal dependencies)

## Development

This is a static website hosted on GitHub Pages with the custom domain `madrigal.mx`.

### Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

## License

© 2026 Madrigal.mx - All rights reserved.
