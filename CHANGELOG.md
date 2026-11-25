# Release notes

## 1.0.10 — 25 November 2026

Karvo LaunchPad 1.0.10 fixes false mod-conflict errors after upgrading from the previous launcher.

- Recognises Fabric API installed automatically by older Karvo launchers on Minecraft 26.2 and 1.21.1.
- Migrates older custom-instance installation records correctly.
- Keeps modified and unrecorded mods intact, and names the affected file when a genuine conflict occurs.

Client **1.0.53** is also available through the launcher for all four supported Minecraft versions. The HUD editor now has only Done on its top bar; use left Ctrl-click or a drag box to select multiple items, and F1 to see keyboard shortcuts. It also includes the recent settings and icon improvements.

Use **Update all** in the launcher. If an earlier launcher keeps displaying the false conflict, install the updated Windows launcher first. Accounts and game data remain in place.

Windows: use **Karvo-LaunchPad-Setup-1.0.10.exe**. Existing macOS/Linux downloads remain available on [KarvoClient.com](https://karvoclient.com/launchpad/) while native account migration is validated.


## 1.0.9 — 25 November 2026

Karvo LaunchPad 1.0.9 brings the native Windows launcher to the main release.

- Replaces the Electron runtime with a native Rust launcher.
- A consistent interface across Home, Versions, Instances, Friends, Console and Settings.
- Dedicated artwork for each Minecraft version and an online-player badge beside More.
- Built-in installation, repair, account switching, Friends, screenshots, notes and launcher updates.
- The installer keeps existing accounts, worlds, servers, mods and other user data in place, and removes the old application runtime after verification.

Download **Karvo-LaunchPad-Setup-1.0.9.exe** for Windows x64. The versioned standalone executable is used by the native updater; use the installer for the first migration from the old launcher.

Existing macOS and Linux downloads remain available on [KarvoClient.com](https://karvoclient.com/launchpad/) while migration of their saved accounts is validated. This release does not change their automatic-update feeds.

Client UI changes, including the keyboard-first HUD editor, are being tested separately and are not included as a client release here.


## Launcher 1.0.3 — 1 November 2026

- Fixes fresh Minecraft 1.8.9 and 1.12.2 client setup when no previous Karvo client has been selected.
- Downloads and verifies the client before preparing its matching performance dependencies.
- Keeps existing verified client selections intact if dependency preparation fails.
- Includes Windows x64, Linux x64/ARM64 and macOS Intel/Apple Silicon installers.

27 targeted updater/dependency tests passed, plus clean client and dependency downloads for both legacy versions. A full game launch on the affected user’s computer remains to be confirmed.

## Launcher 1.0.0 — 28 October 2026

- Refined launcher navigation, settings and Minecraft version selection.
- Improved account switching, verification cooldown handling and update/recovery flows.
- Downloads for Windows, Linux and macOS; the launcher installs the appropriate client.

## Client 1.0.12 — current on 30 October 2026

- HUD editing with dragging/resizing and armour durability display options.
- Durability alerts, inventory fullness, pickup tracking and connection graph modules.
- Saved outfits, server-specific module/HUD profiles and session statistics.
- Screenshot tools, HUD auto-hide, sound subtitles and streamer privacy controls.
- Karvo-built WAILA, Controlling and Mouse Tweaks equivalents.
- Owned-cosmetic/emote locker, configurable emote wheel and two equipped pets.
- Cosmetic, skin-layer, emote, chat and rendering improvements across supported versions.

Launcher and client have separate version numbers. Performance depends on hardware, world and settings; no universal FPS improvement is claimed.
