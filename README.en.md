# Mansur downloads

A Windows input method with optional translation, text-to-speech and speech recognition, provided by individual developer Mansur.

## Latest public test version: 95 (uninstall maintenance correction)

**[Download the 95 Windows x64 test installer (approximately 398 MiB)](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/download/v0.1.0-95/Mansur-Setup-0.1.0.95-Windows-x64.exe)** · [95 release notes and checksum](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-95)

- File: `Mansur-Setup-0.1.0.95-Windows-x64.exe`, **417,234,407 bytes**.
- SHA256: `3241dd68dc95a1900289a077da6b00261f534429161122e50f2ebce14dea7a7a`.
- Fixes generated maintenance records that were not recognized by the uninstall rules and could block cleanup. New rollback records are stored outside the program directory with permission, file-identity and installation-generation checks.
- Completes the explicit version-95 installation, removal and deferred-cleanup checks and rebuilds the maintenance worker. The desktop business executable and browser files remain byte-identical to accepted 94 inputs. The desktop executable still reports 0.1.0.94; Windows setup/removal identifies maintenance revision 95.
- **669 maintenance checks** passed in this round, plus independent payload hashes, compressed integrity and the exact changes from 94. A complete anonymous download matched the published file size and SHA256.
- This remains a **prerelease**: **target-computer installation, installed-version removal, complete installed-browser acceptance and store automatic updates remain pending**.
- Retains the local general context, professional enhancement off by default, dynamic courses, formulas and Chinese answer labels from 94. Local extension 0.3.11 is bundled. It has been submitted to Chrome and Edge review; submission does not establish store publication.
- Version 95 does not rewrite an already-installed older uninstaller. A failed older uninstall must first be recovered using its actual maintenance result. Leave settings, dictionaries, history and model deletion unchecked to preserve data.
- [Version 94 and earlier releases/downloads](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases) remain available, and stable latest is unchanged.

## Accepted version: corrected 92

Known maintenance limitation: an older 92 uninstaller can be affected by the generated-record issue. Version 95 includes the later maintenance corrections but does not rewrite an already-installed 92 uninstaller.

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

Desktop and store-extension versions are published independently. Full neutral page context and professional enhancement in extension 0.3.11 require desktop 94 or maintenance revision 95 (which retains the 94 business executable). Desktop 92 retains the previous general-translation protocol. This GitHub upload does not change either store; 0.3.11 store review and automatic-update acceptance are separate. Check the actual store version.

The 95 installer includes the local 0.3.11 extension files. The browser manages installation, reloading and website permissions separately. Professional enhancement is controlled by one desktop switch, off by default, rather than per-site domain choices. Refresh open pages after changing settings. The new context is local-only; online API and selection translation keep their existing data rules, with no automatic switch to an online provider.

## Historical releases and existing review references

- [Version 91 release](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-91)
- [Version 87 prerelease](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-87)
- [Version 83 review baseline](https://github.com/mabin8121828-crypto/Mansur-Downloads/releases/tag/v0.1.0-83)

These releases and their downloads remain available for existing references. The word `private` in the version 83 filename is historical naming; the asset is public. Historical acceptance results do not automatically apply to version 92.

## Licensing and support

Use the documents bundled with your installer. Version 95 retains the same **2026-10-29.2** documents as 94: [terms](legal/0.1.0.94/使用条款.txt), [privacy notice](legal/0.1.0.94/隐私说明.txt) and [pre-installation notice](legal/0.1.0.94/安装前阅读.txt), matching the documents bundled in 94 and 95.

The original [terms](legal/使用条款.txt), [privacy notice](legal/隐私说明.txt) and [pre-installation notice](legal/安装前阅读.txt) remain historical version87 /2026-10-25.1 material. For 92 and earlier releases, use the documents bundled with each installer.

Mansur-owned code and documentation use [MIT](legal/Mansur-MIT.txt); third-party components and models retain their own licenses. See [license and corresponding-source locations](LICENSES.md). The complete installer is not MIT-only.

This repository publishes downloads and documentation, not the private source repository's Git history. The installer still includes corresponding-source materials required by applicable licenses and some readable Python files.

Support and privacy: **800693@QQ.com**. Include the version, reproduction steps and error message with feedback, but no passwords, verification codes, API keys or private documents.
