# Privacy Policies

Static privacy policy pages for PhotoWerk mobile apps and related services.

The site is built and deployed with GitHub Actions and is available at:

https://cybertechglobal.github.io/privacy_policy/

## Contents

The root `index.html` links to each published policy:

- AvtoFoto
- Optipix
- Carmera
- Catch
- Dienstwagen
- Dekra
- Fotomaister
- MyAutohouse
- Zulassungsschein
- Scan Tires
- GastroCrew
- GastroBot
- Kronex
- Open Source Licenses

Each app has its own folder containing a `privacy_policy.html` file. Shared license information is stored in `license/open-source-licenses.html`.

## Repository Structure

```text
.
├── index.html
├── <app-name>/
│   └── privacy_policy.html
└── license/
    └── open-source-licenses.html
```

## Updating a Policy

1. Edit the matching `<app-name>/privacy_policy.html` file.
2. If adding a new app, create a new folder with `privacy_policy.html`.
3. Add the new policy link to the root `index.html`.
4. Open `index.html` in a browser and verify that all links work.

## Local Preview

Because this is a static site, the pages can be opened directly in a browser. You can also serve the folder locally with any static file server, for example:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.
