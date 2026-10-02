# Koto releases

Koto is a local-first language immersion video player with interactive subtitles, offline dictionaries, vocabulary mining, review, and Anki export. **Koto Free** can currently be used without payment. Koto Plus may add optional paid features later.

## Download

The latest community beta is [Koto Free 1.5.0 for Windows and Linux x64](https://github.com/hirad-ra/Koto-Releases/releases/tag/v1.5.0). Download `Koto-Setup-1.5.0-win-x64.exe` and check it against the attached `SHA256SUMS.txt` before installing. The installer upgrades an existing copy and keeps the local library.

**This community installer is unsigned.** Windows may show SmartScreen or an Unknown Publisher warning. Follow the release notes for the checksum and verification details. Signed production distribution is separate; there is no signed production release yet. Windows 10/11 x64 is the primary installer target. For Linux x64, download `Koto-1.5.0-linux-x64.tar.gz` and verify it with `SHA256SUMS-linux.txt`. Extract it and launch `Koto/Koto.Desktop`; system media/UI dependencies are required.

Version 1.5.0 improves mining responsiveness, player controls, vocabulary review and settings navigation. Streaming quality adapts automatically; audio/subtitle choices and subtitle delay are remembered per video.

## Updates and support

Use **Settings → About → Check for updates**, or visit the [Releases page](https://github.com/hirad-ra/Koto-Releases/releases). Optional notices can be disabled; required checks remain active. Both the [Windows policy](updates/windows-x64.json) and [Linux policy](updates/linux-x64.json) set **1.5.0** as the latest and minimum supported version. Clients below 1.5.0 with update-policy support must upgrade to continue. Older builds without that support cannot be remotely blocked.

For support or a bug report, open an [issue](https://github.com/hirad-ra/Koto-Releases/issues). Review private media, vocabulary, subtitle text, personal paths and logs before sharing them.

Koto application source remains proprietary and private. This repository contains release information, update policy and approved installer/compliance assets. Third-party software and dictionaries retain their own licenses; bundled notices and matching [third-party sources/build information](https://github.com/hirad-ra/Koto-Releases/releases/download/third-party-1.4.0/Koto-Third-Party-Sources-1.4.0.zip) are available. The pinned shared media runtime is unchanged from 1.4.0, so that matching source package is reused.
