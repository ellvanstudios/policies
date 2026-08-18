# Ellvan Studios — Policies

Public, customer-facing policy and support pages for Ellvan Studios apps,
served via GitHub Pages.

**Live site:** https://ellvanstudios.github.io/policies/

## Structure

```
index.html                          landing page (app index)
.nojekyll                           serve files as-is (no Jekyll processing)
figureland/
  privacy/index.html                /policies/figureland/privacy/
voxel-builder/
  privacy/index.html                /policies/voxel-builder/privacy/
  support/index.html                /policies/voxel-builder/support/
```

Each app gets its own top-level folder. Pages use `dir/index.html` so URLs stay
clean (no `.html` extension).

## Adding a new app

1. Create `<app-name>/privacy/index.html` (copy an existing one as a starting point).
2. Add `<app-name>/support/index.html` if the store listing needs a support URL.
3. Link both from the root `index.html`.

## Deployment

GitHub Pages, deploying from the `main` branch at the repository root
(Settings → Pages). Changes go live within a minute or two of pushing to `main`.

## Notes

- These URLs are referenced from Google Play Console. **Do not rename or move
  folders** once an app is live — a dead policy link is a Play compliance flag.
- Public contact address: ellvanstudios@gmail.com
