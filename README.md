# Muhammad Farooq Portfolio — Vercel Package

This folder is ready for deployment as a static Vercel website.

## Deploy through the Vercel dashboard

1. Extract the ZIP file.
2. Create a new GitHub repository and upload all extracted files to the repository root.
3. In Vercel, choose **Add New → Project** and import the repository.
4. Leave **Framework Preset** as **Other**.
5. Leave the build command and output directory empty.
6. Click **Deploy**.

You can also drag the extracted folder into the Vercel CLI workflow using `vercel`.

## Package contents

- `index.html` — complete website structure and interactions
- `assets/` — locally packaged fonts and icon font
- `vercel.json` — static hosting and asset-cache configuration

The contact form is configured as a safe front-end demonstration. Connect your own form service or serverless endpoint before using it for real submissions.
