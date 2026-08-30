# STREET FIGHTER IV — PC — MAY 2009
## Digital Preservation Project

> **Status:** WORKING / PRESERVED  
> **Release:** Original PC release — May 2009  
> **Focus:** digital preservation, provenance, compatibility and historical documentation

[![DOWNLOAD FULL ARCHIVE](https://img.shields.io/badge/DOWNLOAD-FULL%20ARCHIVE-red?style=for-the-badge&logo=icloud)](PASTE_CLOUD_DOWNLOAD_URL_HERE)
---

**Archive size:** ~9.55 GB  
**Format:** ZIP  
**Host:** Cloud storage  
**Contents:** Complete preservation set

> The GitHub repository contains the documentation and catalog.
> The complete archival package is hosted externally.

## 🇧🇷 Sobre

Este projeto documenta uma coleção de materiais relacionados à versão original de **Street Fighter IV para PC**, com foco no lançamento inicial de 2009.

A conservação foi organizada para separar:

- **mídia original de referência**;
- **cópia de trabalho funcional**;
- **componentes legados de compatibilidade**;
- **ferramentas de diagnóstico**;
- **documentação técnica**;
- **material artístico e musical de referência**.

O objetivo é preservar não apenas o jogo, mas o **ambiente histórico de software necessário para reproduzir sua execução** em sistemas modernos.

## 🇺🇸 About

This project documents a collection of materials associated with the **original PC release of Street Fighter IV**, with focus on the initial 2009 release.

The preservation set is organized into:

- **original reference media**;
- **known-working copy**;
- **legacy compatibility components**;
- **diagnostic tools**;
- **technical documentation**;
- **artwork and soundtrack reference material**.

The goal is to preserve not only the game, but the **historical software environment required to reproduce its execution** on modern systems.

---

## 📦 Structure

```text
STREET FIGHTER IV — PC — MAY 2009/
│
├── README.md
├── README.txt
├── CHANGELOG.txt
├── CHECKSUMS.txt
├── PUBLIC_REPOSITORY_PLAN.txt
│
├── 01 — ORIGINAL MEDIA/
│   └── StreetFighter IV.iso
│
├── 02 — WORKING COPY/
│   └── STREET FIGHTERS IV.rar
│
├── 03 — GAMES FOR WINDOWS LIVE/
│   └── gfwlivesetup.zip
│
├── 04 — XLIVE / COMPATIBILITY/
│   ├── xlive.zip
│   ├── Street Fighter IV Crack + CD Key.zip
│   └── Visual C++ All-in-One/
│
├── 05 — DIRECTX/
│   └── directx_Jun2010_redist.exe
│
├── 06 — UNLOCKER / SAVE/
│   └── Street Fighter IV — Unlocker.rar
│
├── 07 — DIAGNOSTICS/
│   ├── Dependencies_x64_Release.zip
│   ├── ProcessMonitor.zip
│   └── ProtectionID.zip
│
├── 08 — DOCUMENTATION/
│   ├── Compatibility.txt
│   ├── Installation_Notes.txt
│   └── Troubleshooting.txt
│
├── 09 — ARTWORKS/
│   └── reference material / metadata
│
└── 10 — ORIGINAL SOUNDTRACK/
    └── reference material / metadata
```

---

## 💿 Original media provenance

**Release:** Argentine retail release  
**Distributor:** Synergex de Argentina

The supplied archival record identifies the source as:

> *Dump of the Argentine release of Street Fighter IV*

According to the supplied source metadata, the disc was dumped twice using **DiscImageCreator/MPF 2.3**, and both dumps matched.

The optical media was checked using:

- CDCheck 3.1.14.0
- VSO Inspector 2.0

**Optical drive:** LG WH14NS40

**Internet Archive identifier:** `sfiv_argentine_release_dump`

---

## 🔐 Reference integrity

The reference ISO checksums are documented in [`CHECKSUMS.txt`](CHECKSUMS.txt).

```text
MD5
023477b92d45ed6def8d003e50441ca7

SHA-1
7d771641557cb1feeaac4c1542c48b26dc8c5214

SHA-256
5892d5bed1311fa47be9097fecc43d3d8f6ca542b5fb480bfab2ee7ac6abb16a

SHA-512
ec753c88c5b6e4884995a99db2de2f11a076559bcd70ad7220c76684254367951e763bebfe2859937535a46547f3f135cb745e4a09372826b7b2055eef7b6abb
```

The reference ISO should remain unchanged. Modified copies belong to the working-copy category.

---

## 🖥️ Known-working configuration

**Tested OS:** Windows 10

**Launcher:** Windows XP Service Pack 3 compatibility mode

### Observed behavior

`StreetFighterIV.exe` may terminate almost immediately when launched directly, without displaying a window or obvious error.

In the tested configuration, the launcher must be started first and used to start the game.

During troubleshooting, **Games for Windows LIVE was uninstalled and reinstalled**, followed by a Windows restart. The game then launched successfully.

This is documented as a **project-specific reproducibility observation**, not a guaranteed universal fix.

---

## 🔧 Diagnostics

The project includes tools useful for investigating silent startup failures:

- Dependencies
- Process Monitor
- ProtectionID
- Windows Event Viewer
- command-line diagnostics

Useful investigation targets include missing DLLs, dependency loading, filesystem/registry access, process creation/termination, compatibility behavior and legacy protection components.

---

## Resources

The collection deliberately separates:

1. **Original Media**
2. **Working Copy**
3. **Games for Windows LIVE**
4. **XLive / Compatibility**
5. **DirectX**
6. **Unlocker / Save**
7. **Diagnostics**
8. **Documentation**
9. **Artworks**
10. **Original Soundtrack**

This distinction allows the project to document what belongs to the historical release versus what was added later to reproduce the software environment.

---

## ☁️ Complete preservation archive

The complete preservation package is intended to be hosted separately from GitHub due to its size and the nature of the included material.

**Complete archive:** *external cloud storage link to be added*

GitHub serves as the public-facing documentation and catalog; the external archive serves as the larger preservation package.

---

## ⚠️ Copyright / distribution

This is a preservation and documentation project.

The original game, executable files, installers, cracks, CD keys, soundtrack, artwork, books and other third-party materials may be protected by copyright or other rights.

**Archival availability does not automatically mean redistribution permission.**

Before publishing copyrighted material publicly, verify the applicable rights and distribution permissions.

This project is not affiliated with **Capcom** or **Microsoft**.

---

## Credits / Provenance

- **Capcom** — original game
- **Synergex de Argentina** — regional release identified by the supplied archival record
- **Microsoft** — Games for Windows LIVE / Windows components
- **DiscImageCreator / MPF** — media dumping tools referenced by the source metadata
- **CDCheck / VSO Inspector** — media verification tools referenced by the source metadata
  
---
### Project Author & Curator

**© 2026 Nicholas S. Felipe — Preservation documentation and project organization.**

**GitHub:**  
[GitHub — file-0](https://github.com/file-0)

**STREET FIGHTER IV — PC — ORIGINAL MAY 2009 BUILD**  
*Digital Preservation Project*
