<p align="center">
  <img src=".assets/feature.png" alt="GTD Plugin for Emby" width="100%">
</p>

# GTD Plugin for Emby

Extends [GTD Launcher](https://github.com/GokuTD/gtd-launcher) with everything that connects it to your Emby server: dynamic wallpapers, an ambient 4K HDR screensaver, native Android TV channels populated from your library, live football overlays, and a built-in Oppo UDP-203 / 205 remote. **Ad-free. No telemetry. No account.**

<p align="center">
  <a href="#"><img alt="Google Play" src="https://img.shields.io/badge/Google_Play-coming_soon-orange.svg"></a>
  <a href="https://gokutd.github.io/gtd-policy/"><img alt="Privacy Policy" src="https://img.shields.io/badge/Privacy-Policy-blue.svg"></a>
  <a href="#premium-features"><img alt="Premium" src="https://img.shields.io/badge/Premium-€7_one--time-gold.svg"></a>
  <a href="https://github.com/GokuTD/gtd-plugin/releases"><img alt="Latest release" src="https://img.shields.io/github/v/release/GokuTD/gtd-plugin?include_prereleases&label=APK"></a>
</p>

> Built by **GTD TV Studio**. Requires [GTD Launcher](https://github.com/GokuTD/gtd-launcher).

## Screenshots

<table>
  <tr>
    <td><img src="screenshots/01_overview.png" alt="Plugin overview"></td>
    <td><img src="screenshots/02_editor.png" alt="Theme editor"></td>
    <td><img src="screenshots/03_wallpaper.png" alt="Animated GL wallpaper"></td>
  </tr>
  <tr>
    <td align="center"><sub>Plugin overview</sub></td>
    <td align="center"><sub>Live theme editor + preview</sub></td>
    <td align="center"><sub>Animated GL wallpapers</sub></td>
  </tr>
  <tr>
    <td><img src="screenshots/04_server.png" alt="Emby connection"></td>
    <td><img src="screenshots/05_screensaver.png" alt="Screensaver"></td>
    <td><img src="screenshots/06_football.png" alt="Football"></td>
  </tr>
  <tr>
    <td align="center"><sub>Emby connection + TMDB</sub></td>
    <td align="center"><sub>4K HDR ambient screensaver</sub></td>
    <td align="center"><sub>Football overlays</sub></td>
  </tr>
  <tr>
    <td><img src="screenshots/07_oppo.png" alt="Oppo remote"></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td align="center"><sub>Oppo player remote</sub></td>
    <td></td>
    <td></td>
  </tr>
</table>

---

## Free tier — what you get without paying

- **Connect to any self-hosted Emby server** (URL + login or Emby Connect with PIN)
- **4 wallpaper themes**: Glass Frosted · Elegant Gold · Midnight + Ken Burns · Neon Cyberpunk
- **Ambient 4K HDR screensaver** — cinematic nature footage + your own Emby backdrops
- **Native Android TV channels**: Continue Watching, Latest Movies, Latest Shows, Live TV with EPG
- **Live TV with PiP** — Picture-in-Picture support from the home screen
- **Football match overlays** — live scores and upcoming match cards; follow your favourite teams or whole competitions (World Cup, LaLiga, Champions League…)
- **TMDB integration** — richer card art (your own free API key)
- **Oppo UDP-203 / 205 remote control** — TCP / HTTP / NFS, works alongside the original Oppo remote
- **Samsung soundbar HDMI input switching** — direct LAN, no internet needed
- 11 fully translated locales

## Premium features

One-time **€7** unlock that opens up:

- **30+ extra wallpaper themes** — covering glass, neon, streaming-style, elegant, vintage, minimal and metallic designs
- **Custom theme editor** — tune gradients, colours, glass panel, positions and animations, save your own themes to the catalog
- **Full Oppo remote mapping** — free tier maps 2 remote keys to Oppo actions, premium unlocks the full mapping catalog and the complete factory defaults

No subscription. No recurring charges. Reinstall and Premium restores from your Google account automatically.

---


## What you'll need

| | |
|---|---|
| **Android TV** with [GTD Launcher](https://github.com/GokuTD/gtd-launcher) installed and set as Home |
| **Self-hosted Emby server** reachable on your LAN |
| (Optional) **TMDB API key** — free at [themoviedb.org/settings/api](https://www.themoviedb.org/settings/api) |
| (Optional) **football-data.org** + **api-football.com** keys — both have free tiers |
| (Optional) **Oppo UDP-203 / 205** for the disc-player remote feature |
| (Optional) **Samsung soundbar with IP Control** for HDMI switching |

The plugin works with Emby alone; everything else is opt-in via the Settings panel.

## Documentation

The plugin docs live in the [GTD Launcher wiki](https://github.com/GokuTD/gtd-launcher/tree/main/docs) — same FAQ and troubleshooting cover both apps. The plugin-specific sections are:

- [FAQ — Plugin & integrations](https://github.com/GokuTD/gtd-launcher/blob/main/docs/FAQ.md#plugin--integrations)
- [Troubleshooting — The plugin (Emby integration)](https://github.com/GokuTD/gtd-launcher/blob/main/docs/Troubleshooting.md#the-plugin-emby-integration)

---

## Install

### Google Play Store

[![Get it on Google Play](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](https://play.google.com/store/apps/details?id=com.gtd.tv.plugin)

> 🟡 Pending Play Store approval. Status will be linked here as soon as the listing goes live.

### Sideload (free APK)

1. Download the latest `GTDPlugin-release.apk` from [Releases](https://github.com/GokuTD/gtd-plugin/releases).
2. Allow unknown sources on your TV: Settings → Security → Unknown apps.
3. Install via [Solid Explorer](https://play.google.com/store/apps/details?id=pl.solidexplorer2) / [X-plore](https://play.google.com/store/apps/details?id=com.lonelycatgames.Xplore) / `adb install GTDPlugin-release.apk`.

The sideloaded APK runs in **free mode** until you purchase Premium via Google Play (the in-app purchase reconciles via the Play Billing client and unlocks the full feature set).

### Mobile companion

For easier setup (Emby login, API keys, IP addresses) install **GTD Setup** on your phone — paired by QR code from the launcher's Setup wizard. Available from the [GTD Launcher releases](https://github.com/GokuTD/gtd-launcher/releases).

---

## Support

- **Bugs / feature requests** → [open an issue](https://github.com/GokuTD/gtd-plugin/issues/new/choose)
- **Email** → gokukinto@gmail.com
- **Privacy Policy** → https://gokutd.github.io/gtd-policy/

This repository hosts the public-facing README, screenshots, releases and issue tracker. The application source is closed; the repo contains no code.

---

© 2026 GTD TV Studio · All rights reserved
