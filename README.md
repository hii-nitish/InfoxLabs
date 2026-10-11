# InfoxLabs website

A plain static site. No build step.

## Files
- `index.html` the one-page site
- `privacy.html`, `terms.html` legal pages
- `404.html` not-found page
- `styles.css` all styling
- `fonts/` self-hosted Outfit font
- `favicon.svg` browser tab icon
- `netlify.toml` Netlify settings and security headers

## Change the contact email
The email address appears in `index.html`, `privacy.html` and `terms.html`. Search for `hello@your-domain.com` and replace it in all three files.

## Deploy on Netlify
1. Push these files to a GitHub repository (files at the top level of the repo).
2. In Netlify choose Add new site, then Import an existing project, then GitHub, and pick the repo.
3. Leave the build command empty and set the publish directory to `.` (a dot), then deploy.
4. In Site configuration, change the site name to get a free address like `your-name.netlify.app`.
