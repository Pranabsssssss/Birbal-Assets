# Birbal Assets — Next.js

Development

1. Install dependencies:

```bash
npm install
```

2. Start dev server:

```bash
npm run dev
```

Open http://localhost:3000

## Cloudflare Workers

Deploy with `npm run deploy`. In Cloudflare Workers Builds, set the deploy command to `npm run deploy` so OpenNext builds the Worker before Wrangler publishes it.

Notes
- Place files under `public/assets` to have them listed by the app.
- API endpoint: `/api/assets` returns a JSON array of `{url,name,ext}`.
