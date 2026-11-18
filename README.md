# InkLedger

Tattoo consent and procedure records platform — early prototype.

## Run
Open `index.html` in a modern browser, or deploy the repository through GitHub Pages (Settings → Pages → Deploy from a branch → main → /root).

## Current demo
Six steps: client information, medical questionnaire, tattoo details, sample legal acknowledgments, signature drawing, artist review. All data remains in the current browser page; refreshing clears it. No backend, persistent storage, real cloud uploads, verified legal waiver, or production-grade signature process is implemented.

## Security
**Do not enter real client names, birthdates, medical details, ID images, or other sensitive data.** This public repository contains demo source code only. Never commit client data or credentials.

## Planned architecture
Next.js web frontend, authenticated API, PostgreSQL with tenant isolation, encrypted private document storage, location-specific cloud export connectors, attorney-reviewed legal templates, camera capture, lot tracking, and audit trails.

## Legal
Prototype text is not legal advice or an enforceable production consent agreement. Obtain jurisdiction-specific legal review before real-world use.
