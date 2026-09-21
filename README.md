# Kallubi BSV Explorer

Independent Bitcoin SV (BSV) explorer UI.

Live: [kallubi-bsv-explorer.de](https://kallubi-bsv-explorer.de)

Not affiliated with WhatsOnChain or the BSV Association. Information only. No accounts, no custody, no keys.

## What it does

- Address / TX / block lookup via public WhatsOnChain APIs
- Live node status from the Kallubi pruned node
- Richlist, labels, activity heuristics (not identity)
- Wallet downloads (v1.0.3 Linux / Windows / Mac M1+)
- Watchlist in the browser (LocalStorage)
- DE / EN, dark / light

## What it does not do

- It does not store seeds or private keys
- Lookups still use WhatsOnChain; the wallet broadcasts via the Kallubi node
- Prebuilt hosting is convenience; this repo is the source to review

## Run locally

Static files. Open `index.html` or use any static host (Cloudflare Pages).

Wallet binaries stay in R2 / the live site, not in this repo.

## License

MIT — see `LICENSE`.
