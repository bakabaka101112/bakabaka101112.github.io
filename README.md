# Engr. Lalaine Aubrey T. Solano Portfolio

A Vite + React portfolio site for a structural-focused civil engineer. The design uses a black and warm gold visual system and is configured for GitHub Pages deployment.

## Local development

```bash
pnpm install
pnpm dev
```

## Build

```bash
pnpm build
```

## Publish to GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`.

1. Push to the `main` branch.
2. In GitHub, open **Settings > Pages**.
3. Set **Build and deployment** to **GitHub Actions**.
4. The workflow builds the Vite app and publishes `dist`.

For a custom LinkedIn button, set `linkedinUrl` in `src/App.jsx`.
