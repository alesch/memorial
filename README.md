# memorial

Static memorial site for Annica Ågren.

## What this is

A single static page (`index.html`, `style.css`, plus `images/` and
`audio/` assets) with no build step or backend.

## Deployment

The site is deployed via **GitHub Pages**, serving directly from this
repository (the `master` branch). Any commit pushed to `master` is
published automatically at:

```
https://alesch.github.io/memorial/
```

To publish a change, push to `master` — no build or release step is
required.

## Incoming redirect

This site is the destination of the short link `http://qr.schenkman.info/a`,
which is generated and redirected from the
[`alesch/qr`](https://github.com/alesch/qr) repository (a QR code deployed
on Vercel). Anyone scanning that QR code lands here. If this site's URL
ever changes, update the redirect `destination` in `alesch/qr`'s
`vercel.json` accordingly.
