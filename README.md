# ServiceProof Website

Static public website and App Store listing reference for ServiceProof.

## Local preview

```bash
cd /Users/xiangguazi/Documents/private_work/ansio/project/ServiceProof-Website
python3 -m http.server 8788
```

Open `http://localhost:8788`.

## GitHub Pages

Publish from the `main` branch and the repository root. `.nojekyll` keeps GitHub Pages from applying Jekyll processing.

Before App Store submission, replace the pre-release support-contact placeholder in `support.html` with the monitored public support address, then update this site.

## Public domain

GitHub Pages is configured for `serviceproof.ansiotech.cn`. The DNS provider must keep a
`CNAME` record for the `serviceproof` host pointing to `ansiotech.github.io`; do not change
the separate `api` or `auth` hosts used by the app backend and email links.
