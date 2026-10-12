# Deployment notes

1. Create a new public GitHub repository, for example `carely-healthcare-demo`.
2. Upload every file in this package directly into the repository root. Do not create an assets subfolder; all images are in the same folder as `index.html`.
3. In Cloudflare Pages, connect the new repository.
4. Select the branch that actually exists in GitHub (typically `main`).
5. Framework preset: `None`.
6. Build command: leave blank, or enter `exit 0` if the interface requires a command.
7. Build output directory: `.`.
8. Deploy, then open the generated `*.pages.dev` URL and test the mobile menu, clinician search/filter, booking flow, and profile preview.

This is a static front-end demonstration. To make booking real, connect a secure backend and scheduling system, add authentication and authorization, and complete privacy, security, accessibility and applicable healthcare compliance reviews before handling patient data.
