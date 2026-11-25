# Karvo LaunchPad

## Latest Windows release: 1.0.9

[Download the native Windows launcher](https://github.com/dev2cge/KarvoLaunchPad-Releases/releases/download/v1.0.9/Karvo-LaunchPad-Setup-1.0.9.exe) · [Release notes](https://github.com/dev2cge/KarvoLaunchPad-Releases/releases/tag/v1.0.9)

The native Rust Windows launcher preserves existing accounts and game data during installation. Existing macOS/Linux downloads remain available at [KarvoClient.com](https://karvoclient.com/launchpad/).


Official launcher downloads, release notes, support and performance-testing resources for Karvo LaunchPad.

[Download the launcher](https://github.com/dev2cge/KarvoLaunchPad-Releases/releases/latest) · [Website](https://karvoclient.com/launchpad/) · [Report a problem](https://github.com/dev2cge/KarvoLaunchPad-Releases/issues/new/choose)

Karvo LaunchPad is a Minecraft Java Edition launcher and integrated client, with configurable HUD modules, cosmetics, emotes and account management. Supported game versions are 1.8.9 and 1.12.2 (Forge), and 1.21.1 and 26.2 (Fabric).

The native Windows launcher is **1.0.9**. Existing Linux x64/ARM64 and macOS Intel/Apple Silicon downloads remain available on the website while native migration of their saved accounts is validated. Client updates are managed separately by the launcher. A valid Minecraft Java Edition account is required. Optional cosmetics and Karvo+ are paid separately.

## Download verification

Download an installer and SHA256SUMS.txt from the same release. On Windows use Get-FileHash; on Linux use sha256sum; on macOS use shasum -a 256. Compare the complete digest. A matching hash verifies the downloaded bytes against this release; it is not an independent security audit.

Windows builds currently use Karvo's self-signed certificate. Windows may display Unknown Publisher or SmartScreen warnings. These builds do not carry a publicly trusted publisher certificate. macOS availability does not constitute a claim of Apple notarisation. Obtain downloads only here or at karvoclient.com.

## Support and transparency

See [support](SUPPORT.md), [release notes](CHANGELOG.md), [benchmark protocol](benchmarks/README.md), [media kit](media/README.md) and [community partnerships](community/PARTNERSHIPS.md).

This repository contains public distribution and support materials. The application source remains private. It is not an open-source release of the launcher or client, and no independent audit or platform endorsement is claimed. No standalone client JAR is distributed here; the launcher manages client installation.

Not affiliated with or endorsed by Mojang, Microsoft or other Minecraft clients.
