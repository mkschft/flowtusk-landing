# Flowtusk Landing Page

This is the marketing website for Flowtusk — a Webflow to HubSpot form integration service.

## Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+)
- [pnpm](https://pnpm.io/) package manager

### Getting Started

1. Install dependencies:
```bash
pnpm install
```

2. Start the development server with auto-reload:
```bash
pnpm run dev
```

This will:
- Start the local server on http://localhost:3000
- Start browser-sync on http://localhost:3001 (use this URL for development)
- Auto-reload the browser when you edit HTML, CSS, or JS files

### Manual Server Start

If you prefer to run without auto-reload:
```bash
node server.js
```

Then visit http://localhost:3000

## Project Structure

```
├── css/              # Stylesheets
├── js/               # JavaScript files
├── images/           # Image assets
├── *.html            # HTML pages
├── server.js         # Development server
├── package.json      # Dependencies and scripts
└── .gitignore        # Git ignore rules
```

## Deployment

This site is deployed to GitHub Pages. Push to the main branch to deploy.

## Notes

- The server serves static files with proper MIME types
- All routes serve the corresponding HTML file (e.g., `/privacy-policy.html`)
- CSS and JS files are properly linked with relative paths
