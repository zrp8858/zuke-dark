# zukeDark

A dark resource pack for Minecraft 26.3 by **zrp8858**.

**Status: work in progress -- nothing released yet.**

Goals: simplistic GUI containers and interfaces with a nod to the container
that opened each menu, one consistent feel across every screen (including
modded ones), a sleeker font that still fits Minecraft, and reworked ore
textures.

## Requirements

- Minecraft 26.3 (resource pack format 97)

## License

Not decided yet -- pending the license of the pack this one is based on.
Until a `LICENSE.md` is added here, treat everything in this repository as
all rights reserved.

## Contributions

This is a personal project and isn't accepting pull requests. Bug reports are
welcome via issues.

---

## For developers

The repository root *is* the pack root (`pack.mcmeta` lives here). To make an
installable pack, zip the contents of this folder so that `pack.mcmeta` sits
at the top level of the zip, leaving out `.git/`.

Two folders are intentionally untracked (see `.gitignore`) and exist only on
the author's machine: `ideas/` (planning notes) and `source-material/`
(reference assets from other packs).
