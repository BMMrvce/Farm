# Deploy on Vercel

This project is configured as a static site.

## Entry URL

- `/` -> rewrites to `demo-docs/index.html`

## Quick Deploy Steps

1. Push this folder to a Git repository (GitHub/GitLab/Bitbucket).
2. In Vercel, click **Add New Project** and import the repository.
3. Framework preset: **Other**.
4. Build command: leave empty.
5. Output directory: leave empty.
6. Deploy.

## Optional CLI Deploy

1. Install Vercel CLI: `npm i -g vercel`
2. From project root run: `vercel`
3. For production run: `vercel --prod`

## Notes

- `vercel.json` handles root routing and cache headers.
- All client-facing docs are printable HTML files in `demo-docs/`.
