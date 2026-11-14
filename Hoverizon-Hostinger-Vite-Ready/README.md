# Hoverizon — Hostinger deployment

Production build verified successfully. Existing page styling retained.

## GitHub / automated build
Upload the project files with package.json at the repository root (extract ZIP first).
Node.js: 22.12 or newer.
Install command: npm ci
Build command: npm run build
Output directory: dist

## Direct file upload
Upload only the contents of dist/ into your domain public_html folder, so index.html is directly inside public_html. Do not upload node_modules.

## Local development
npm ci
npm run dev
