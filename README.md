# Max Iglesias — Engineering Portfolio

A responsive, static personal website with a dark homepage and a light project-detail page. No build tools are required.

## Local preview

Open `index.html` in a web browser. The homepage links to `projects.html`.

## Before publishing

1. In `index.html` and `projects.html`, replace `YOUR_EMAIL@example.com` with your professional email address.
2. In `index.html`, replace `YOUR_LINKEDIN` with your actual LinkedIn public-profile slug.
3. Proofread all experience/project claims and make sure you are comfortable publishing them.
4. Only add photos, CAD images, drawings, or technical details you own or have permission to publish. Visuals already included are original CSS/SVG illustrations, not company material.
5. Optionally add an authorized resume PDF to the folder and link it in the navigation.

## Publishing to GitHub Pages (no command line)

1. Log into https://github.com and click **New repository**.
2. Name it `YOUR_GITHUB_USERNAME.github.io` for a root site, or `engineering-portfolio` for a project site.
3. Set visibility to **Public**, then create the repository.
4. Choose **Add file → Upload files**, upload `index.html`, `projects.html`, `styles.css`, and `script.js` from this folder, and commit them to the `main` branch.
5. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, select `main` and `/ (root)`, and save.
6. Visit `https://YOUR_GITHUB_USERNAME.github.io/` (root site) or `https://YOUR_GITHUB_USERNAME.github.io/engineering-portfolio/` (project site) after deployment completes.

The relative file links work in either repository layout. GitHub Pages may take several minutes to deploy. A custom domain can be configured later through Settings → Pages after purchasing the domain and creating the required DNS records.

## Site structure

- `index.html`: homepage, experience, about, contact
- `projects.html`: light-background project summaries
- `styles.css`: styling and responsive layout
- `script.js`: mobile menu and copyright year

## What to add next

- Approved project photos, original CAD renders, and measured results
- A real resume PDF and a download button
- A GitHub link and a custom domain
- Additional personal/class projects with documentation

## Color scheme

Ember Orange + Black: charcoal `#0c0c0e`, primary orange `#ff7417`, warm white `#f8f5f1`. Edit the custom color overrides at the end of `styles.css` to adjust the theme.
