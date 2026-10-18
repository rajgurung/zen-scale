# zen-scale.io

Homepage for Zen Scale Ltd. Astro static site, hosted on Cloudflare Pages.

```bash
npm install
npm run dev      # local dev server
npm run build    # outputs dist/
npm run deploy   # manual build and deploy to the zen-scale Pages project
```

Pushes to `main` deploy automatically through `.github/workflows/deploy.yml`. It needs the `CLOUDFLARE_API_TOKEN` and `CLOUDFLARE_ACCOUNT_ID` repo secrets.

Content lives in `src/pages/index.astro`. Styles and theme tokens are in `src/styles/global.css`.
