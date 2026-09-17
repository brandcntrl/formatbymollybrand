# format. by molly — brand deck site

This folder is the brand deck, served at brand.formatbymolly.com. It is separate from the app, which lives at www.formatbymolly.com in the `formatbymolly.github.io` repository.

## put it online

1. In the `formatbymolly` GitHub account, create a second public repository. Call it `brand`.
2. Upload `index.html`, `CNAME` and `favicon.png` to its root.
3. Settings → Pages → Source: Deploy from a branch → `main`, `/ (root)` → Save.
4. Custom domain: `brand.formatbymolly.com` → Save. When the DNS check passes, tick **Enforce HTTPS**.

## DNS

Wherever formatbymolly.com is managed, add one record alongside the existing `www` one:

| type | name | value |
|---|---|---|
| CNAME | brand | formatbymolly.github.io |

On Cloudflare, set it to DNS only.

## the two codes

- `qr-app-white.png` → www.formatbymolly.com (the app)
- `qr-brand-white.png` → brand.formatbymolly.com (the deck)

Both are white on transparent, so they need a dark ground. Ink versions are included for light grounds.
