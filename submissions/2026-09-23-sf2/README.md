# Syphon Filter 2 catalog submission

This packet proposes one new owned-input PlayStation setup title. The file pins its public source fallback commit, the complete ordered Redump media identity for both discs with every digest, and an explicit SCPH1001 BIOS identity.

| Title | Release | Discs | JSON |
|---|---|---|---|
| Syphon Filter 2 | [v0.2.0](https://github.com/alexbeavs-ps1-ports/syphon-filter-2-recomp/releases/tag/v0.2.0) | 2 | [syphon-filter-2-psx.json](syphon-filter-2-psx.json) |

- Source fallback: `bb588c8b54f910ccc05b10b5cef8a695c75fdfb6` (the tagged release commit).
- Discs: SCUS-94451 (Disc 1, boot) and SCUS-94492 (Disc 2), one track each, in `rom_identity.discs[]`.
- BIOS: SCPH1001 (512 KiB, SHA-256 `71af94d1e47a68c11e8fdb9f8368040601514a42a5a399cda48c7d3bff1e99d3`).
- Release assets: Windows x64, Linux x64, macOS ARM64 and macOS x64 setup zips plus `RELEASE-MANIFEST.json` and `SHA256SUMS.txt`.
