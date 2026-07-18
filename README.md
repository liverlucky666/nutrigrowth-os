# NutriGrowth OS

NutriGrowth OS is a static, interactive competition demo for a trustworthy nutrition-brand content growth workflow.

## Deployment

Vercel is connected to this repository. Each push to `main` creates a production deployment; other branches and pull requests create preview deployments.

The runtime contains only:

- `index.html`
- `assets/electrolyte-product.png`
- `assets/protein-product.png`

No build command, server runtime, API key, or environment variable is required.

## Local Preview

```powershell
py -3 -m http.server 4173
```

Open `http://127.0.0.1:4173/`.

## Data Boundary

Consumer records and experiment metrics in the demo are structured sample data. Public sources support exploration but do not replace enterprise SKU labels, testing records, approvals, or production integrations.
