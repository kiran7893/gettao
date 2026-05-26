# gettao

Static CSI CDR dashboard for Vercel.

## Vercel deploy settings

The repo includes `vercel.json`, so Vercel should use these settings automatically:

- Framework Preset: Other
- Output Directory: `public`
- Build Command: leave empty

The deployed entry point is `public/index.html`. CSV files are intentionally ignored by `.vercelignore`; load mapping and CDR data through the dashboard's CSV upload controls after opening the site.
