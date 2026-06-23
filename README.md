# Dodsons Yard Care website

This is the static website for [elidodson.com](https://elidodson.com). It has no
build step and can be hosted directly from the repository root.

## Local preview

Open `index.html` in a browser, or run a small local web server from this folder.

## Hosting configuration

Recommended host: Cloudflare Pages connected to a private GitHub repository.

- Production branch: `main`
- Framework preset: None
- Build command: leave blank
- Build output directory: `/`
- Root directory: `/`

Once connected, every push to `main` deploys automatically. Other branches can
be used for preview deployments.

## Before launch

- Add the purchased domain under the Pages project's **Custom domains** screen.
- Follow Cloudflare's displayed DNS instructions at the domain registrar.
- Test the `www` and root-domain versions, HTTPS, and email links.
