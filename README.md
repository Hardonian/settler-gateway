# Settler Gateway

Intended: a Cloudflare Worker gateway in front of the Settler FinOps platform —
edge auth, rate limiting, and request routing.

Current status: **scaffold only.** This repo currently contains just a
`wrangler.toml` placeholder. No worker code is implemented yet.

## Planned

- `wrangler.toml` — Worker config (account/site bindings).
- `src/index.ts` — edge handler: validate requests, forward to the Settler
  backend, add CORS + basic rate limiting.
- Deploy via `wrangler deploy`.

## Not yet built

Do not expect a working gateway from this repo. Implementation is pending.
