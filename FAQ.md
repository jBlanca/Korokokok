# Frequently Asked Questions

## What is Korokokok v0.9?

Korokokok v0.9.2 is the first public **Early Access** release. It ships as a $69 perpetual license with a built-in 14-day free trial.

- **14-day free trial** — install, run, decide. Every feature unlocked, no card required up front.
- **$69 perpetual license** — buy at any time during or after the trial. Activate on up to 3 machines. [Buy a license](https://buy.polar.sh/polar_cl_LD4BO6w75fCJkYiK4vjZgfnfp7PXZ3sZKxax71rN8wr).
- **Free upgrade to v1.0** (regular price $99) for every Early Access buyer.
- After day 14 without a license, the Editor / Visual / Narration / Music workspaces lock. Project Manager, Assembly Line, and Tools Sandbox stay free forever.
- Auto-update is disabled in this build — you'll download new installers manually until auto-update lands.

## When does v1.0 launch?

When it's ready. Every Early Access license includes a free upgrade to v1.0 (regular $99), plus all Early Access updates while v1.0 is in development. There's no separate waitlist — just buy at the Early Access price now and you're covered through v1.0.

## Does Korokokok work offline?

Yes. All AI generation — images, narration, music — runs on your local GPU and CPU. After the initial model download, no internet connection is required. Trial day-count and license activation are checked at runtime; everything else stays local.

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
- **Text-to-speech** runs on CPU on non-NVIDIA systems in this Early Access build (GPU acceleration planned for a later release)

If you only have an integrated GPU, narration and image generation still work but expect noticeably slower generation times.

## What happens after the 14-day trial?

- **Project Manager**, **Assembly Line**, and **Tools Sandbox** stay free forever.
- **Editor**, **Visual**, **Narration**, and **Music** workspaces lock until you [buy a license](https://buy.polar.sh/polar_cl_LD4BO6w75fCJkYiK4vjZgfnfp7PXZ3sZKxax71rN8wr) and activate it. You can buy at any time — your projects, settings, and downloaded models stay put.

## How large are the AI models?

The installer itself is ~117 MB. AI models and runtime components download on first use, only for the tools you choose to install — typically 10–15 GB total depending on which features you use. The Downloads panel in Settings lets you pick which engines to install.

## Does it support languages other than English?

- **Narration**: multiple languages — up to 646 languages supported across the bundled engines (breadth varies by engine).
- **Image generation** prompts work best in English but accept other languages.
- **Story analysis** is primarily English-tuned at launch.

## Why does Windows SmartScreen warn me when I install it?

Because v0.9.2 isn't yet signed with a commercial code-signing certificate (~$200–400/year). SmartScreen warns on every unsigned app from an unknown publisher — it's not saying the software is malicious, it's saying "I don't have a reputation record for this publisher yet." A signed certificate is planned for around the v1.0 launch. Click **More info → Run anyway** to proceed.

Every release includes a SHA-256 hash in its release notes so you can verify the binary yourself.

## My antivirus flagged the binary — is it malware?

No. Indie apps without a code-signing certificate are sometimes flagged by heuristic antivirus engines because the publisher is unknown.

## Can I use the generated content commercially?

Yes — content you create is 100% yours. We claim no rights over your generated images, audio, or projects. Some bundled open-source models have their own output licensing terms — generally permissive for commercial use. Full attribution is in `THIRD_PARTY_LICENSES.txt` inside the installed app's `resources/` folder.

## How do I support the project?

The most direct way is to [buy a license](https://buy.polar.sh/polar_cl_LD4BO6w75fCJkYiK4vjZgfnfp7PXZ3sZKxax71rN8wr) — Early Access purchases directly fund development through v1.0 and beyond. If you want to add an extra tip on top, [Ko-fi](https://ko-fi.com/korokokokstudio) is also there.

## How do I report a bug or request a feature?

Open an issue on GitHub: [Bug Report](https://github.com/jBlanca/Korokokok/issues/new?template=bug_report.yml) or [Feature Request](https://github.com/jBlanca/Korokokok/issues/new?template=feature_request.yml). You can also email [korokokok.storystudio@gmail.com](mailto:korokokok.storystudio@gmail.com).

## Who built Korokokok?

Korokokok is developed by an independent creator — Joel Blanca — focused on giving storytellers a fully-local, offline-first production studio.
