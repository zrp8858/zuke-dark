# zukeDark

A dark resource pack for Minecraft 26.3 by **zrp8858**.

**Status: work in progress -- nothing released yet.**

Goals: simplistic GUI containers and interfaces with a nod to the container
that opened each menu, one consistent feel across every screen (including
modded ones), a sleeker font that still fits Minecraft, and reworked ore
textures.

## Requirements

- Minecraft 26.3 (resource pack format 97)

## What's in it so far

- **Font:** [Slightly Improved Font (32x)](https://modrinth.com/resourcepack/slightly-improved-font)
  by Lat -- a sharper redraw of the vanilla font, included unmodified under
  its MIT license.

## License

zukeDark's own license isn't decided yet. Until a `LICENSE.md` is added here,
treat everything that is original to this repository as all rights reserved.

Third-party work included in the pack stays under its own license -- see
[THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for what's included and the
required notices.

## Contributions

This is a personal project and isn't accepting pull requests. Bug reports are
welcome via issues.

---

## For developers

The repository root *is* the pack root (`pack.mcmeta` lives here). To make an
installable pack, zip the contents of this folder so that `pack.mcmeta` sits
at the top level of the zip.

**Leave `.git/`, `ideas/`, `source-material/` and `dev-client/` out of the
zip.** The last three are intentionally untracked (see `.gitignore`) and exist
only on the author's machine: `ideas/` (planning notes), `source-material/`
(other people's packs, kept for private reference -- most of them are all
rights reserved and must never be redistributed) and `dev-client/` (a local
Gradle project that launches Minecraft with this pack for testing). Zipping the
whole folder from a file manager would include them, so build the zip from a
clean checkout or exclude those folders explicitly.
