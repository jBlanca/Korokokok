# Changelog

All notable changes to Korokokok will be documented in this file.

The project follows [Semantic Versioning](https://semver.org/). Pre-1.0 releases are Early Previews — feature-complete but not yet commercially released.

## [0.9.2] — 2026-05-13 — Early Access

### Highlights
- **Early Access pricing live** — $69 perpetual license via Polar, with 14-day free trial as the on-ramp; activates on up to 3 machines; includes free upgrade to v1.0 (regular $99)
- **14-day trial** (up from 7 days) — more breathing room to download models and explore
- **Smaller installer** (~117 MB) — components you don't need on day one download on first use, only if you ask for that feature
- **Smoother first-run setup** — entering Visual / Narration / Music opens a tool picker filtered to what's compatible with your hardware, with sizes and running totals shown upfront
- **Hardware-aware setup wizard** — only lists components your machine can actually run; a Rescan button next to the Hardware heading lets you re-detect after upgrading your GPU
- **Cleaner Settings → Downloads** — every installable AI tool listed by name with plain-language descriptions and sizes; install or uninstall individual tools without reinstalling the whole app
- **Smarter Sandbox (Tools)** — empty states with a jump-to-Downloads button when a tool's model isn't installed; the Sandbox itself never triggers downloads
- **Tighter System tab** — streamlined to detected GPUs, active GPU, and performance profile; redundant inventory removed
- **Cleaner uninstall** — uninstaller asks whether to also delete downloaded models and generated content; defaults to keeping your data

### Notes
- v0.9.1 was retired and replaced by v0.9.2; only v0.9.2 is available on the Releases page

## [0.9.0] — 2026-04-22 — Early Preview

First public release. **Free 14-day preview** of the full product while the commercial v1.0 release is in preparation.

### Highlights
- Story import and scene segmentation (documents, PDFs, markdown)
- Entity extraction — characters, locations, objects, with multi-angle portraits and costume libraries
- Image generation with character-consistent editing (low-VRAM tier supports 8 GB cards)
- Narration with 60+ voices across 28 languages, expressive TTS, voice cloning, and multilingual engines covering hundreds of languages
- Original AI-generated soundtracks with 20 curated singer voices and style/mood/instrumentation controls
- Assembly Line for packaging final assets
- Animatic video rendering with Ken Burns pan-and-zoom, burned-in subtitles, and narration mixing

### Preview-specific notes
- Auto-update is disabled — download new releases manually when they ship
- No purchase flow yet — the Lemon Squeezy store will be live at v1.0
- Optional Ko-fi support page at [ko-fi.com/korokokokstudio](https://ko-fi.com/korokokokstudio)
- Waitlist: email korokokok.storystudio@gmail.com with subject "Korokokok v1.0 launch waitlist" for early-supporter pricing notice

### Security & licensing
- Proprietary EULA shown at install
- Third-party attribution in `resources/THIRD_PARTY_LICENSES.txt`

### Known limitations
- Windows only (macOS/Linux not planned for v1.0)
- Image generation works on AMD/Intel GPUs (slightly slower than NVIDIA); TTS on non-NVIDIA systems falls back to CPU in this preview
- Windows SmartScreen will warn on install (unsigned binary until commercial signing cert is acquired post-launch) — verification SHA-256 published in release notes
