# FAIR Utility Data

Live content data for the FAIR utility comparison app.

The app reads `fair-data.json` from GitHub Pages so provider, region, and pricing information can be updated without rebuilding the Android app.

## Update Workflow

1. Edit `fair-data.json`.
2. Keep valid JSON and preserve the top-level keys:

```json
{
  "schemaVersion": 1,
  "updatedAt": "2026-06-22T00:00:00.000Z",
  "countries": {},
  "providers": {}
}
```

3. Commit and push the change.
4. GitHub Pages publishes the updated file.

Live URL:

```text
https://jacobfox83-arch.github.io/fair-utility-data/fair-data.json
```
