# WLOC GPS Worker

Standalone Cloudflare Worker deployment for the WLOC location picker and map-link parser.

## One-click deploy

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/bq328/wlocgps)

Direct link:

https://deploy.workers.cloudflare.com/?url=https://github.com/bq328/wlocgps

## Manual deploy

```bash
npm ci
npx wrangler login
npm run deploy
```

Source adapted from https://github.com/cyberhandyman/wloc-spoofer-en
