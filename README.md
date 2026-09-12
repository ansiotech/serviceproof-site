# ServiceProof Website

Static public marketing, legal, and support website for ServiceProof.

## Local preview

```bash
cd /Users/xiangguazi/Documents/private_work/ansio/project/ServiceProof-Website
python3 -m http.server 8788
```

Open `http://localhost:8788`.

## GitHub Pages

Publish from the `main` branch and the repository root. `.nojekyll` keeps GitHub Pages from applying Jekyll processing.

The public site must not include internal App Store metadata checklists, review credentials, submission instructions, or non-public operational details.

## Public domain

GitHub Pages is configured for `serviceproof.ansiotech.cn`. The DNS provider must keep a
`CNAME` record for the `serviceproof` host pointing to `ansiotech.github.io`; do not change
the separate `api` or `auth` hosts used by the app backend and email links.
