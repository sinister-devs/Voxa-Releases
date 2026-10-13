# Voxa downloads

Official Dev and Prod installer repository. Application and backend source code are maintained separately in private repositories.

## Download

**[Download Voxa Dev 27.54 for Mac](https://github.com/sinister-devs/Voxa-Releases/releases/download/v27.54-macos-dev-beta.1/Voxa-27.54-universal.dmg)**

- macOS 14 or later; Apple Silicon and Intel.
- Universal drag-to-install DMG. The app is labelled Voxa Dev.
- [Release notes and SHA256 checksums](https://github.com/sinister-devs/Voxa-Releases/releases/tag/v27.54-macos-dev-beta.1).
- [Инструкция на русском](INSTALL.ru.md).

This is a **Dev beta** using your own OpenAI API key and separate provider billing. The server-connected Prod Free/Premium product is not published here yet. Windows installers have not been migrated into this repository; Android is not available.

## Install

1. Download the DMG and check its SHA256 against SHA256SUMS.txt in the release.
2. Open the DMG and drag Voxa.app into Applications. Quit the old app before replacing it.
3. Launch Voxa Dev from Applications and configure your API key, microphone, Accessibility access and shortcuts.

The app is signed with an Apple Development certificate. This beta is **not Developer ID signed or notarized**. macOS may block first launch: verify the source/checksum, then use System Settings → Privacy & Security → Open Anyway if appropriate. Do not disable Gatekeeper.

The same app identifier is used by earlier Mac beta builds. Back up local history and recordings before updating. Automatic paste and correction learning depend on the target editor and macOS permissions. Review generated text before sending it.

Your API key is stored in macOS Keychain. Audio and text needed for requested AI processing are sent to the configured provider. Local automated and package checks do not establish provider availability, microphone quality or compatibility with every editor. Do not put API keys, recordings or private text in public issues.

Only approved binaries, relative checksums and user documentation belong in this repository. No application source, credentials, personal screenshots or local histories.
