# My Village Decor — redesign concept

A pitch/demo redesign of [myvillagedecor.com](https://www.myvillagedecor.com), built by Legend Websites to show the owner what a modern rebuild could look like.

Not the client's live site — a standalone concept hosted at `myvillagedecor.legendwebsites.co.uk`.

## Structure

- `website/` — static site (HTML/CSS/JS), served as Cloudflare Worker assets
- `worker.js` — asset-serving Worker
- `wrangler.jsonc` — deploy config, routes `myvillagedecor.legendwebsites.co.uk`

## Deploy

```
npx wrangler deploy
```
