# Neon Ninja Run Website

Astro static site for `neonninjarun.com`, built for GitHub Pages.

## Local setup

```sh
cd website
npm install
npm run dev
```

## Build

```sh
cd website
npm run build
```

## GitHub Pages

The workflow at `.github/workflows/deploy-neon-site.yml` builds this folder and publishes the `dist` output to GitHub Pages.

In GitHub, enable:

- Settings > Pages > Source: GitHub Actions
- Custom domain: `neonninjarun.com`

Update `public/app-ads.txt` with the real AdMob publisher ID before launch.
