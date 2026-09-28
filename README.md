# Godseye Technologies

Marketing website for [godseyetechnologies.com](https://godseyetechnologies.com/).

The application lives in `site/` and builds as a static Vite site for Cloudflare Pages.

## Local development

```bash
cd site
npm install
npm run dev
```

## Cloudflare Pages

| Setting | Value |
|---|---|
| Production branch | `main` |
| Root directory | `site` |
| Build command | `npm run build` |
| Build output directory | `out` |

Every push to `main` produces a new production deployment through the connected Cloudflare Pages project.
