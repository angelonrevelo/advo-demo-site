![HTML](https://img.shields.io/badge/HTML-static-E34F26?logo=html5&logoColor=white)
![Cloudflare Pages](https://img.shields.io/badge/deploy-Cloudflare%20Pages-F38020?logo=cloudflare&logoColor=white)
![status](https://img.shields.io/badge/status-demo-lightgrey)

# advo-demo-site

**A one-page placeholder used to test deploying to Cloudflare Pages.**

This is not a product. The whole repo is a single `index.html` that shows the
heading "ADVO Demo" and the line "Sample project deployed to Cloudflare Pages".
It exists to prove a deploy pipeline works end to end, nothing more.

## Quick start

There is no build step and no dependencies. Open the file directly:

```bash
open index.html
```

or serve the folder with any static server, e.g.:

```bash
python3 -m http.server 8000
```

## Deploy

Point a Cloudflare Pages project at this repo with no build command and the
repo root as the output directory.
