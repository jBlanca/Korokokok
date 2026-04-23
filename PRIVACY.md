# Privacy Policy

_Last updated: 2026-04-22_

Korokokok is designed to run fully offline on your computer. This policy explains what happens with your data.

## What we collect from the app itself

**Nothing.** Korokokok does not collect, transmit, or store any user data on external servers. Your stories, generated images, audio, and project files all stay on your local machine.

There is no telemetry, no analytics, no crash reporting, and no usage tracking built into the application.

## What leaves your computer

Korokokok makes a small number of outbound network requests, each strictly scoped:

- **Model and binary downloads** from our CDN ([cdn.korokokok.app](https://cdn.korokokok.app), hosted on Cloudflare R2). Your client sends only the filename being requested; no user content or machine identifiers are included. The full list of downloadable files is published at [cdn.korokokok.app/manifest.json](https://cdn.korokokok.app/manifest.json) with SHA-256 hashes so you can audit exactly what gets fetched.
- **v0.9 Early Preview** does NOT make any license-related network calls. Trial dates are tracked locally via `license.json`, Windows Registry, and hidden backup files on your own PC.
- **Auto-update checks** are DISABLED in v0.9. When auto-updates are enabled in a future release, checks will only send a version string to our update endpoint.
- **Voluntary Ko-fi tips** (if you choose to support the project) open a browser to [ko-fi.com/korokokokstudio](https://ko-fi.com/korokokokstudio). Ko-fi handles all payment data under its own privacy policy — Korokokok never sees card numbers, addresses, or payment details.

## Future commercial release (v1.0+)

Once Korokokok v1.0 launches with paid licensing, the following will apply:

- **Payment processing** will be handled by Lemon Squeezy (an EU-based merchant of record). See their [privacy policy](https://www.lemonsqueezy.com/privacy). Korokokok will not see your card details.
- **Your email** will be collected by Lemon Squeezy at checkout to deliver your license key and receipt. It may be used by the Korokokok team to email you about critical updates, license issues, or optional notices you've opted into (such as the v1.0 waitlist).
- **License activation** will validate your license key online once at install time, then cached for 30 days of offline use. Only the license key and a machine fingerprint (used to enforce the 2-device limit) are sent. No story content, generated assets, or personal files ever leave your computer.

## AI models

All AI generation (images, narration, music) runs on your local GPU and CPU. Prompts and generated content are never sent to any third-party AI service. Models are downloaded once from our CDN and stored locally.

## Your files

Story content, project files, generated assets, and voice recordings are stored only in the locations you choose on your own computer. We have no access to them.

## Waitlist email

If you email us at [korokokok.storystudio@gmail.com](mailto:korokokok.storystudio@gmail.com) to join the v1.0 launch waitlist, we'll keep your email address privately and use it **once** to notify you when v1.0 ships with early-supporter discount pricing. You can ask to be removed at any time.

## Contact

Questions about this policy: [korokokok.storystudio@gmail.com](mailto:korokokok.storystudio@gmail.com)
