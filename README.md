# Lucya Services Site

Static HTML presentation for Lucya, focused on the current SaaS services:

- WhatsApp assistant for service businesses
- appointment scheduling with explicit confirmation
- availability blocks and rescheduling flow
- tenant admin assistant by WhatsApp
- follow-ups, reminders and client notifications
- campaign quota, outbox logs and provider routing
- Evolution + Meta Cloud API readiness
- multi-tenant security and auditability

## Local preview

Open `index.html` directly in the browser or serve the folder with any static server.

## Cloudflare Pages

This project is ready for direct upload:

```bash
npx wrangler pages deploy . --project-name=lucya-services-site
```

Wrangler must be authenticated with `wrangler login` or `CLOUDFLARE_API_TOKEN`.
