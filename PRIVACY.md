# Privacy Policy

_Last updated: 2026-05-13_

Korokokok is designed to run fully offline on your computer. This policy explains what happens with your data.

## What we collect from the app itself

**Nothing.** Korokokok does not collect, transmit, or store any user data on external servers. Your stories, generated images, audio, and project files all stay on your local machine.

There is no telemetry, no analytics, no crash reporting, and no usage tracking built into the application.

## What leaves your computer

Korokokok makes a small number of outbound network requests, each strictly scoped:

- **Model and binary downloads** from our CDN ([cdn.korokokok.app](https://cdn.korokokok.app), hosted on Cloudflare R2). Your client sends only the filename being requested; no user content or machine identifiers are included. The full list of downloadable files is published at [cdn.korokokok.app/manifest.json](https://cdn.korokokok.app/manifest.json) with SHA-256 hashes so you can audit exactly what gets fetched.
- **License activation** (Early Access onward) validates your license key with our licensing endpoint. Only the license key and a machine fingerprint (used to enforce the 3-machine activation limit) are sent. No story content, generated assets, or personal files leave your computer during activation.
- **Trial day-count** is tracked locally via `license.json`, Windows Registry, and hidden backup files on your own PC. The trial itself does not require any network call.
- **Auto-update checks** are DISABLED in v0.9.2. When auto-updates are enabled in a future release, checks will only send a version string to our update endpoint.
- **Voluntary Ko-fi tips** (if you choose to support the project) open a browser to [ko-fi.com/korokokokstudio](https://ko-fi.com/korokokokstudio). Ko-fi handles all payment data under its own privacy policy — Korokokok never sees card numbers, addresses, or payment details.

## Payment processing

- **Payments are handled by Polar** (an EU-based merchant of record). See their [privacy policy](https://polar.sh/legal/privacy). Korokokok never sees your card details.
- **Your email** is collected by Polar at checkout to deliver your license key and receipt. It may also be used by the Korokokok team to contact you about critical updates or license issues.

## AI models

All AI generation (images, narration, music) runs on your local GPU and CPU. Prompts and generated content are never sent to any third-party AI service. Models are downloaded once from our CDN and stored locally.

## Your files

Story content, project files, generated assets, and voice recordings are stored only in the locations you choose on your own computer. We have no access to them.

## Contact

Questions about this policy: [korokokok.storystudio@gmail.com](mailto:korokokok.storystudio@gmail.com)
