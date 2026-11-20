# Essex County Atlas

Maps of Essex County, New Jersey, by census tract and decade (1940–2020), built with [maplibre-yaml](https://docs.maplibre-yaml.org/).

- Pages: `index.html` and `essex-*.html`
- Map settings: `maps/essex-*.yaml`
- Data: `data/` (GeoJSON made from IPUMS NHGIS extracts)

Every push to `main` publishes the site with GitHub Pages (`.github/workflows/deploy.yml`).

The NHGIS API key goes in `data/apitxt.txt`. It is listed in `.gitignore` and must never be committed.
