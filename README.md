# HollowPatch

Hollow Knight IPA patched with `hollowknight://` URL scheme for integration with [Main Menu](https://github.com/Elderflowa/main-menu) app launcher.

## Installation

### Via AltStore (Recommended)
1. Open AltStore on your iPhone
2. Go to **Sources** → **+** → Add: `https://raw.githubusercontent.com/Elderflowa/HollowPatch/main/source.json`
3. Install "Hollow Knight" from the source

### Direct IPA Install
Download `HollowKnight.ipa` from [Releases](https://github.com/Elderflowa/HollowPatch/releases) and install via Feather, Sideloadly, or AltStore.

## Features
- **Bundle ID:** `dev.elder.hollowknight` (separate from App Store version)
- **URL Scheme:** `hollowknight://` — launch from Main Menu or any app
- **Compatible:** iOS 13.0 - 18.0
- **Based on:** Hollow Knight v1.5.78

## Main Menu Integration
1. Open Main Menu
2. Add/edit Hollow Knight entry
3. Tap **"Find URL schemes"** → select `hollowknight://`
4. Test launch

## Updating
Trigger the **Update IPA Release** workflow with a new version number when you have a new patched IPA.