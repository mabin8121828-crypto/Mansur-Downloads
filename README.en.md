# Mansur downloads

A Windows input method with optional translation, text-to-speech and speech recognition, provided by individual developer Mansur.

## Latest public test version: 94

**[Download the 94 Windows x64 test installer (approximately 398 MiB)](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-94/Mansur-Setup-0.1.0.94-Windows-x64.exe)** · [94 release notes and checksum](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-94)

- File: `Mansur-Setup-0.1.0.94-Windows-x64.exe`, **417,285,140 bytes**.
- SHA256: `e2e00ec633ccf2508caeb3e23511eaf035eeabb9b8014c643ae69ce7db09296c`.
- Version 94 is a **prerelease**. Archive integrity and relevant isolated checks passed; **target-computer installation, complete installed-browser acceptance and store automatic updates remain pending**. The accepted 92 release remains below.
- Local general whole-page translation uses bounded visible labels, table headers and nearby sentences to disambiguate words, without requiring professional enhancement.
- Professional enhancement is off by default and controlled centrally in desktop settings. Select a domain and independently opt into an imported glossary; Chrome and Edge follow the same setting. Complete industry dictionaries are not bundled.
- Dynamic course pages, formulas and Chinese answer labels are retained. The installer includes local extension 0.3.11; this does not establish its publication in either browser store.
- The exact checked installer was uploaded without a rebuild. A complete anonymous download matched its size and SHA256.

## Accepted version: corrected 92

**[Download the version 92 Windows x64 installer (approximately 398 MiB)](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-92/Mansur-Setup-0.1.0.92-Windows-x64.exe)** · [Version 92 release notes and checksum](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-92) · [中文](README.md)

- Windows 10 version 2004+ / Windows 11, Intel or AMD x64.
- File: `Mansur-Setup-0.1.0.92-Windows-x64.exe`, **417,327,301 bytes**.
- SHA256: `ed70efcb46eb6b834145444b2baf65ced723e5fff366d40b27c50ce933dba86e`.
- This is the existing corrected installer, published unchanged without recompilation or repackaging. A complete anonymous download matched its exact size and SHA256.
- On 2026-10-29 the user confirmed that corrected 92 installed and worked normally. This does not establish comprehensive acceptance on other devices or of all features. The installer is not digitally signed.

Version 92 provides the desktop support needed by browser extension 0.3.6 for whole-page Chinese translation, automatic translation after refresh, and dynamic content. It also fixes the installation checks, maintenance and stale Word registration conflicts addressed in this release. Whole-page translation defaults to local models; users may explicitly select their own configured online API. Online services may charge fees, and the two modes do not silently switch between each other.

Download the **EXE**. GitHub's automatic **Source code (zip / tar.gz)** archives contain this download repository's documentation, not an installable input method.

## Installation and data

1. Save your work and close active Mansur learning, speech or settings operations.
2. Open the EXE and read its bundled terms, privacy notice, installation instructions and component licenses before accepting. Follow normal Windows prompts for this unsigned installer; disabling security controls is not required.
3. Follow the installer's checks for an existing installation. If removal is required, settings/API configuration, dictionaries, records and models have separate deletion choices, **off by default**. Leave deletion options unchecked to retain them. An incomplete-removal message does not mean uninstallation succeeded.
4. Follow the setup guide and select Mansur with Win + Space. Direct upgrades from every older version are not claimed.

Ordinary typing needs no large model. Optional translation, speech and dictation require their respective models or selected services. The installer does not include all optional models, developer API keys or online allowances. Model and speech resources may require several GB of downloads. The model downloader prioritizes domestic ModelScope sources; actual availability and speed depend on the network and source service. The downloader does not require a VPN. Reuse existing models without unnecessary downloads or relocation.

## Chrome and Edge

[Chrome Web Store](https://chromewebstore.google.com/detail/mansur/dmenmlbpnfajdnjnbjkcdldmhmfpphgb) · [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/mansur/aoinocgeagdfogjpmjbpcndapplmjidl)

Desktop and store-extension versions are published independently. Full neutral page context and professional enhancement in extension 0.3.11 require desktop 94. Desktop 92 retains the previous general-translation protocol. This GitHub upload does not change either store; 0.3.11 store review and automatic-update acceptance are separate. Check the actual store version.

The94 installer includes the local 0.3.11 extension files. The browser manages installation, reloading and website permissions separately. Professional enhancement is controlled by one desktop switch, off by default, rather than per-site domain choices. Refresh open pages after changing settings. The new context is local-only; online API and selection translation keep their existing data rules, with no automatic switch to an online provider.

## Historical releases and existing review references

- [Version 91 release](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-91)
- [Version 87 prerelease](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-87)
- [Version 83 review baseline](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-83)

These releases and their downloads remain available for existing references. The word `private` in the version 83 filename is historical naming; the asset is public. Historical acceptance results do not automatically apply to version 92.

## Licensing and support

Use the documents bundled with your installer. Version 94 uses document version **2026-10-29.2**: [terms](legal/0.1.0.94/使用条款.txt), [privacy notice](legal/0.1.0.94/隐私说明.txt) and [pre-installation notice](legal/0.1.0.94/安装前阅读.txt), matching the bundled 94 documents.

The original [terms](legal/使用条款.txt), [privacy notice](legal/隐私说明.txt) and [pre-installation notice](legal/安装前阅读.txt) remain historical version87 /2026-10-25.1 material. For 92 and earlier releases, use the documents bundled with each installer.

Mansur-owned code and documentation use [MIT](legal/Mansur-MIT.txt); third-party components and models retain their own licenses. See [license and corresponding-source locations](LICENSES.md). The complete installer is not MIT-only.

This repository publishes downloads and documentation, not the private source repository's Git history. The installer still includes corresponding-source materials required by applicable licenses and some readable Python files.

Support and privacy: **800693@QQ.com**. Include the version, reproduction steps and error message with feedback, but no passwords, verification codes, API keys or private documents.
