# DIVERTI marketing website

An independent Astro static site for the upcoming DIVERTI iPhone app.

## Local development

```sh
npm install
npm run dev
```

Astro prints the local preview URL (usually http://localhost:4321). To create and
preview a production build, run `npm run build` and `npm run preview`.

## Structure

- `src/pages/index.astro` — homepage
- `src/layouts/BaseLayout.astro` — document shell and shared styles
- `public/` — static assets

The site is configured for static output and the `diverti.app` production URL.
No deployment workflow, repository, or DNS configuration is included yet.
