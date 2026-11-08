# Portfolio

## Local development

```sh
npm ci
npm run dev
```

Create a production build with `npm run build`; Astro writes the static site to `dist/`.

## GitHub Pages deployment

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys the site when changes are pushed to `main` or `master`.

To enable deployment:

1. Push this repository to GitHub.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. Configure `phuongpham.com` with the DNS records required by GitHub Pages, then verify the domain and enable HTTPS in **Settings → Pages**.

The `public/CNAME` file and `site` setting in `astro.config.mjs` configure the custom domain for the generated site.
