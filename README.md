# Koto releases

Koto is a language immersion video player with interactive subtitles, offline dictionaries, vocabulary mining, review and Anki export. Local features are free without an account. A free account adds your profile, achievements and earned themes. AI and cloud sync require Kiwami access on your account.

## Download

Download [Koto 1.6.0 for Windows and Linux x64](https://github.com/hirad-ra/Koto-Releases/releases/tag/v1.6.0).

- Windows 10/11 x64: `Koto-Setup-1.6.0-win-x64.exe`. The installer includes its runtime and media tools and preserves your existing Koto library.
- Linux x64: `Koto-1.6.0-linux-x64.tar.gz`. Extract it and run `Koto-linux-x64/Koto.Desktop`. Requires glibc 2.38+, libstdc++ with GLIBCXX 3.4.32, and your distribution's media/UI dependencies listed in the release notes. No .NET installation is required.

Check downloads against the attached SHA256SUMS files. This community release is unsigned; Windows may show SmartScreen or an Unknown Publisher warning. Follow the release notes before proceeding.

There is no new Mac installer in 1.6.0. The Mac update policy remains at 1.5.1 while the native Mac build is completed and validated.

## Updates and support

Use **Settings → About → Check for updates**, or visit [Releases](https://github.com/hirad-ra/Koto-Releases/releases). Windows/Linux policies advertise 1.6.0 while keeping the minimum supported version at 1.5.0.

For support, open an [issue](https://github.com/hirad-ra/Koto-Releases/issues). Review private media, vocabulary, subtitles, personal paths and logs before sharing them.

Koto application source remains proprietary and private. This repository contains release information, update policies and approved binary/compliance assets. Linux uses native compilation and includes no managed .NET assemblies or Koto C# source. Windows uses obfuscation. Third-party software and dictionaries retain their own licenses. The Windows shared media runtime is unchanged from the reviewed 1.4.0 inputs, so the matching [third-party sources](https://github.com/hirad-ra/Koto-Releases/releases/download/third-party-1.4.0/Koto-Third-Party-Sources-1.4.0.zip), build information and license archives are reused.
