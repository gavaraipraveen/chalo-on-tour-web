
# Deployment instructions (Netlify)

1. Create a GitHub repository and push this project.
2. On Netlify, click **New site from Git** and connect your GitHub repo.
3. Set build command: `npm run build`
4. Set publish directory: `dist`
5. Deploy site.
6. In Netlify app settings:
   - In "Identity" tab, enable Identity.
   - In "Identity > Services", enable Git Gateway.
   - In "Settings > Build & deploy > Environment", ensure `NETLIFY_AUTH_TOKEN` is set if needed.
7. Open `https://<your-site>.netlify.app/admin` to login and use Netlify CMS.

Notes:
- Netlify CMS uses `git-gateway` backend which requires Netlify Identity + Git Gateway enabled.
- Media (images) will be stored in `static/img`.
