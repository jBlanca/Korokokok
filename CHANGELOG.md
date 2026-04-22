# Changelog

All notable changes to Korokokok will be documented in this file.

The project follows [Semantic Versioning](https://semver.org/). Pre-1.0 releases are Early Previews — feature-complete but not yet commercially released.

## [0.9.0] — 2026-04-22 — Early Preview

First public release. **Free 7-day preview** of the full product while the commercial v1.0 release is in preparation.

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
- Waitlist: email hello@korokokok.app with subject "Korokokok v1.0 launch waitlist" for early-supporter pricing notice

### Security & licensing
- Proprietary EULA shown at install
- Third-party attribution in `resources/THIRD_PARTY_LICENSES.txt`

### Known limitations
- Windows only (macOS/Linux not planned for v1.0)
- Image generation works on AMD/Intel GPUs (slightly slower than NVIDIA); TTS on non-NVIDIA systems falls back to CPU in this preview
- Windows SmartScreen will warn on install (unsigned binary until commercial signing cert is acquired post-launch) — verification SHA-256 published in release notes
