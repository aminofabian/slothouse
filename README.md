# Slothouse.cc → Slothouse.io notice page

Static closure notice for **slothouse.cc**. Point DNS for `slothouse.cc` at this site so visitors learn the brand has moved to [slothouse.io](https://slothouse.io/).

## Stack

Plain HTML / CSS / JS — no build step. Drop on any static host (Cloudflare Pages, Netlify, S3, nginx, etc.).

## Local preview

```bash
cd slothouse-landing
python3 -m http.server 4174
```

Open http://localhost:4174/?noredirect=1

## Deploy notes

1. Point `slothouse.cc` (and `www` if used) at the static host.
2. Confirm HTTPS and that `/` serves `index.html`.
3. Auto-redirect sends players to `https://slothouse.io/` after 10s (cancelable; `?noredirect=1` skips it).

## Copy

Edit `index.html` if you need stronger language around balances, account migration, or support contact.
