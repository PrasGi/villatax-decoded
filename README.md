# VillaTax Decoded

A one-page, static product teardown of [VillaTax](https://villa-tax.operium.store): feature map, data flow, third-party integrations, Indonesian tax engine, business model and findings.

There is no build step and no dependencies. Open `index.html` in a browser.

## Files

```
index.html        the whole page (HTML, CSS and JS inline)
shots/            HD screenshots used in the Findings section
.nojekyll         tells GitHub Pages to serve files as-is
```

## Run locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deploy to GitHub Pages

1. Create a new **public** repository on GitHub (for example `villatax-decoded`) and push this folder to its `main` branch.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then click **Save**.
4. After a minute or two the page is live at:

```
https://<your-github-username>.github.io/villatax-decoded/
```

Anyone with that link can open it. GitHub Pages on a free account requires the repository to be public.

## Sources

Public pages on villa-tax.operium.store and the read-only VillaTax demo workspace, reviewed on 1–2 November 2026. Figures marked as demo are VillaTax sample data.
