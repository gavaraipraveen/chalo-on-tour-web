
# Chalo On Tour - Static Site (Eleventy) + Netlify CMS

This project is a starter for the **Chalo On Tour** travel website, using Eleventy (11ty) as a static site generator and **Netlify CMS** as the admin panel to manage packages.

## What is included
- Eleventy templates (src/)
- Content folder: content/packages (markdown files created by Netlify CMS)
- Netlify CMS admin: admin/index.html and admin/config.yml
- Static assets: static/ (css, images)
- Build: `npm run build` produces the site in `dist/`

## How to use
1. Install dependencies:
   ```bash
   npm install
   ```
2. Run locally:
   ```bash
   npm run start
   ```
   Eleventy will serve the site at http://localhost:8080

3. Deploy on Netlify:
   - Push this repo to GitHub
   - Create a new site on Netlify and connect the GitHub repo
   - Build command: `npm run build`
   - Publish directory: `dist`
   - Enable Identity and Git Gateway on Netlify to use Netlify CMS.

See the detailed deployment steps in the included `DEPLOY.md`.
