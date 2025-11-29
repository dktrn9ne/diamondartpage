# Diamond Art Page

Simple static page that renders an animated pink sparkle grid from `index.html`.

## Deploying to Vercel

1. Install the Vercel CLI if you do not already have it:
   ```bash
   npm install -g vercel
   ```
2. From the repository root, log in (or link) to your Vercel account:
   ```bash
   vercel login
   vercel link
   ```
3. Deploy the static site:
   ```bash
   vercel --prod
   ```

The included `vercel.json` config uses the static file builder for `index.html` and routes all paths to that file so you can reach the page at the root or any subpath.
