# Lucya Services Site

Static HTML presentation for Lucya.

## Local preview

Open `index.html` directly in the browser or serve the folder with any static server.

## Cloudflare Pages

This project is ready for direct upload:

```bash
npx wrangler pages deploy . --project-name=lucya-services-site
```

Wrangler must be authenticated with `wrangler login` or `CLOUDFLARE_API_TOKEN`.
