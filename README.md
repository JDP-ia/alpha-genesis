# Alpha-Genesis Construction Corp.

Static multi-page website for Alpha-Genesis Construction Corp., designed for Cloudflare Pages.

## Local preview

```bash
python3 -m http.server 8080
```

The contact form uses FormSubmit, a free static-host-compatible form relay, and sends submissions to `alphagenesisconstruction@gmail.com`.

## Cloudflare Pages

Use `rebuild-wix-site` as the production branch. No build command is required; publish the repository root. Add `alphagenesisconstruction.com` as a custom domain in Cloudflare Pages, then point the domain DNS to the Pages project as instructed by Cloudflare.
