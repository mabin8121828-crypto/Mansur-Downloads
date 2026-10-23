# Mansur downloads

A Windows input method with optional translation, text-to-speech and speech recognition, provided by individual developer Mansur.

## Version 83 — test release

**[Download the Windows x64 installer (approximately 398 MiB)](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-83/Mansur-Setup-0.1.0-private.83-Windows-x64.exe)** · [Release notes and checksum](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-83) · [中文](README.md)

- Windows 10 version 2004 or later / Windows 11, Intel or AMD x64.
- This release uses the existing, validated version 83 repair installer without rebuilding it for publication. `private` in its filename is historical version naming; the download is public.
- Size: **416,919,533 bytes** (approximately 398 MiB).
- SHA256: `8bfaa7845d8f9c1032078d272e94d606b0ef2ecfc608735ba2ba0eb210bd22cc`.
- This installer is **not code-signed**. Check the download source and checksum.

Download the **EXE**, not GitHub's automatically generated Source code ZIP/tar.gz. Those archives contain only this download repository's documentation.

## Installation

Save your work, run the installer, read the [terms](legal/使用条款.txt), [desktop privacy notice](legal/隐私说明.txt) and component licenses, then accept the terms to continue. Follow the setup guide and select Mansur using Windows' input-method switcher (Win + Space).

Ordinary typing does not require a large model. Optional translation and text-to-speech require models or service configuration according to the selected mode; local speech recognition requires its recognition model. Models are downloaded after confirmation; the installer does not include all optional models.

## Browser integration and limitations

The Chrome and Edge extensions are both named **Mansur**, version **0.3.3**. Drafts have been saved in both developer dashboards; neither has been submitted for review or published. Store links will be added when available.

This installer includes the corrected Edge extension identity and connection-registration migration, together with browser-extension fixes for first site enablement and cold start. Existing version 83 installations can be upgraded through the installer.

This repair installer passed an actual upgrade from the previous version 83 on a second Windows computer, verification of 2,815 installed files and related registration checks, and connections and public sample translations with the existing test extensions after reopening Chrome and Edge. Installation from the official stores remains to be verified after review and publication. These checks do not establish complete clean-system, Word, live-microphone or compatibility-matrix coverage.

## Licenses and contact

Mansur-owned code and documentation use the [MIT license](legal/Mansur-MIT.txt). Third-party components retain their own licenses, including GPL/LGPL where applicable. See [license and corresponding-source locations](LICENSES.md). This download repository contains no history from the project's source repository; the installer itself includes applicable corresponding-source materials and some readable Python files.

The supplied terms and privacy documents are in Chinese. Contact **800693@QQ.com** for support or privacy requests. Do not send passwords, verification codes, API keys or private documents.
