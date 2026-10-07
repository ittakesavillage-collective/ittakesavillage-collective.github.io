# It Takes a Village hub

The public front door for the It Takes a Village collective's apps: one page, one QR code.

- `index.html`: the hub. App cards are driven by the `APPS` list in its script. Set `live: true`
  on an app once it is published at its path (`/hurley/`, `/willian/`, `/flawedhero/`).
- `privacy.html`: privacy notice.
- `assets/`: collective logo, icons, app card images.

Served by GitHub Pages from this repo (`mbroadbent-code.github.io`). Each app is its own repo and
appears at `<domain>/<repo-name>/` automatically once the custom domain is set here.
