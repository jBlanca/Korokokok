# Frequently Asked Questions

## What is Korokokok v0.9?

Korokokok v0.9 is a **free 7-day Early Preview** of the full product. It's the first public build shared while the commercial release is still being finalized.

- All features are unlocked for 7 days after install.
- No account, no credit card, no sign-up required.
- After day 7, the Editor / Visual / Narration / Music workspaces lock. Project Manager, Assembly Line, and Tools Sandbox stay free forever.
- Auto-update is disabled in this preview — you'll download a new installer when v1.0 ships.

## When does the paid v1.0 launch?

Soon. The commercial release with one-time purchase licensing is in preparation. Email [hello@korokokok.app](mailto:hello@korokokok.app?subject=Korokokok%20v1.0%20launch%20waitlist) with subject *"Korokokok v1.0 launch waitlist"* and we'll send a one-time heads-up when v1.0 is live, plus early-supporter discount pricing.

## Does Korokokok work offline?

Yes. All AI generation — images, narration, music — runs on your local GPU and CPU. After the initial model download, no internet connection is required. Even the v0.9 trial date is tracked locally; there's no online license check in this preview.

## Is my data sent anywhere?

No. Your stories, generated images, audio, and project files stay on your computer. There is no telemetry, no cloud sync, and no analytics. See [PRIVACY.md](PRIVACY.md) for details.

## What hardware do I need?

**Minimum**: Windows 10 64-bit, NVIDIA GPU with 8 GB VRAM, 16 GB RAM, 20 GB free disk space.
**Recommended**: Windows 11, NVIDIA GPU with 16 GB VRAM+, 32 GB RAM, 80 GB free disk space.

8 GB VRAM users get the full image-editing feature set — same visual quality at 480p, ~60–90s per image. Full requirements in the [README](README.md#system-requirements).

## Does it work on Mac or Linux?

Not currently. Korokokok is Windows-only at launch.

## Does it work with AMD or Intel GPUs?

Partially:

- **Image generation** works on AMD/Intel GPUs (slightly slower than NVIDIA)
- **Text-to-speech** runs on CPU on non-NVIDIA systems in this preview (GPU acceleration planned for a later release)

If you only have an integrated GPU, narration and image generation still work but expect noticeably slower generation times.

## What happens after the 7-day trial?

- **Project Manager**, **Assembly Line**, and **Tools Sandbox** stay free forever.
- **Editor**, **Visual**, **Narration**, and **Music** workspaces lock until you install v1.0 with a valid license (when that ships).

## How large are the AI models?

The installer itself is ~525 MB; it bundles everything needed to run on the broadest range of NVIDIA drivers out of the box. AI models download on first run and depend on which features you use — typically 10–15 GB total. The Downloads panel in Settings lets you pick which engines to install.

## Does it support languages other than English?

- **Narration**: multiple languages — up to 646 languages supported across the bundled engines (breadth varies by engine).
- **Image generation** prompts work best in English but accept other languages.
- **Story analysis** is primarily English-tuned at launch.

## Why does Windows SmartScreen warn me when I install it?

Because v0.9 isn't yet signed with a commercial code-signing certificate (~$200–400/year). SmartScreen warns on every unsigned app from an unknown publisher — it's not saying the software is malicious, it's saying "I don't have a reputation record for this publisher yet." A signed certificate is planned for around the v1.0 launch. Click **More info → Run anyway** to proceed.

Every release includes a SHA-256 hash in its release notes so you can verify the binary yourself.

## My antivirus flagged the binary — is it malware?

No. Indie apps without a code-signing certificate are sometimes flagged by heuristic antivirus engines because the publisher is unknown.

## Can I use the generated content commercially?

Yes — content you create is 100% yours. We claim no rights over your generated images, audio, or projects. Some bundled open-source models have their own output licensing terms — generally permissive for commercial use. Full attribution is in `THIRD_PARTY_LICENSES.txt` inside the installed app's `resources/` folder.

## How do I support the project during the preview?

If Korokokok has saved you time, you can drop a tip on [Ko-fi ☕](https://ko-fi.com/korokokokstudio). Fully optional — the preview is free either way.

## How do I report a bug or request a feature?

Open an issue on GitHub: [Bug Report](https://github.com/jBlanca/Korokokok/issues/new?template=bug_report.yml) or [Feature Request](https://github.com/jBlanca/Korokokok/issues/new?template=feature_request.yml). You can also email [hello@korokokok.app](mailto:hello@korokokok.app) or [korokokok.studio@gmail.com](mailto:korokokok.studio@gmail.com).

## Who built Korokokok?

Korokokok is developed by an independent creator — Joel Blanca — focused on giving storytellers a fully-local, offline-first production studio.
