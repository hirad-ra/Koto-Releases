# Koto releases

Koto is a local-first language immersion video player with interactive subtitles, offline dictionaries, vocabulary mining, review, and Anki export. **Koto Free** can currently be used without payment. Koto Plus may add optional paid features later.

## Download

The latest community beta is [Koto Free 1.4.6 for Windows and Linux x64](https://github.com/hirad-ra/Koto-Releases/releases/tag/v1.4.6). Download `Koto-Setup-1.4.6-win-x64.exe` and check it against the attached `SHA256SUMS.txt` before installing. The installer upgrades an existing copy and keeps the local library.

**This community installer is unsigned.** Windows may show SmartScreen or an Unknown Publisher warning. Follow the release notes for the checksum and verification details. Signed production distribution is separate; there is no signed production release yet. Windows 10/11 x64 is the primary installer target. For Linux x64, download `Koto-1.4.6-linux-x64.tar.gz` and verify it with `SHA256SUMS-linux.txt`. Extract it and launch `Koto-linux-x64/Koto.Desktop`; system media/UI dependencies are required.

Version 1.4.6 adds **R** to replay audio while reviewing flashcards. Version 1.4.5 automatically downloads a missing dictionary for recognized subtitles, with definitions in the interface language (currently English), and shows download/installation progress with Cancel and Retry.

## Updates and support

Use **Settings → About → Check for updates**, or visit the [Releases page](https://github.com/hirad-ra/Koto-Releases/releases). Optional automatic notices can be disabled in Settings; required security/compatibility checks remain active. The public [Windows update policy](updates/windows-x64.json) is temporarily testing **1.4.6** as both the latest and minimum supported versions. The [Linux policy](updates/linux-x64.json) uses the same requirement. Version 1.4.6 is now published and satisfies this unchanged requirement. Clients below 1.4.6 with policy support remain blocked until upgraded. Older builds without update-policy support cannot be remotely blocked.

For support or a bug report, open an [issue](https://github.com/hirad-ra/Koto-Releases/issues). Review private media, vocabulary, subtitle text, personal paths and logs before sharing them.

Koto application source remains proprietary and private. This repository contains release information, update policy and approved installer/compliance assets. Third-party software and dictionaries retain their own licenses; bundled notices and matching [third-party sources/build information](https://github.com/hirad-ra/Koto-Releases/releases/download/third-party-1.4.0/Koto-Third-Party-Sources-1.4.0.zip) are available. The pinned shared media runtime is unchanged from 1.4.0, so that matching source package is reused.
