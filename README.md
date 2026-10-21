# Relay IPTV

Relay is an IPTV player for **Android TV, Google TV, Fire TV, and Android phones and tablets**. Sign in with the Xtream Codes details from your IPTV provider and get a fast, remote-friendly TV app.

Relay doesn't provide any channels or content. It only plays what your own provider gives you.

## Download

**[relay-iptv.apk](https://github.com/Beechey/relay-releases/releases/latest/download/relay-iptv.apk)** — always the latest version.

This link never changes, so it's easy to type into the *Downloader* app on a TV or Fire TV stick:

```
https://github.com/Beechey/relay-releases/releases/latest/download/relay-iptv.apk
```

Android asks you to allow installs from that app the first time. After that, Relay checks this page for new versions and installs them when you agree, keeping your login and settings.

## What it does

- **Live TV** with a preview player, channel groups, favourites and a *Recent* group
- **TV guide** built from your provider's full XMLTV listings
- **Movies and series** with posters, details, seasons and an episode list inside the player
- **Continue watching** and *Up next* for series, plus recently watched rows on Home
- **Search** across everything, or inside any category
- **Hide categories** you never watch, with multi-word filters
- **Audio, subtitles and quality** per video, including Dolby and DTS audio
- **Picture-in-picture** on phones and tablets
- **Several playlists**, a refresh schedule, and detailed settings

## Getting started

1. Open Relay and enter your provider's **server address** (with the port, e.g. `http://example.com:8080`), **username** and **password**.
2. Relay downloads your channels, movies, series and guide. A big playlist takes a minute the first time; after that it opens straight away.
3. Relay keeps you signed in on that device.

| | TV remote | Phone / tablet |
|---|---|---|
| Select | OK | Tap |
| Options, favourite, hide a category | Hold OK | Press and hold |
| Change channel (fullscreen) | Up / Down | Swipe up / down |
| Skip in a movie | Left / Right | Double-tap left / right |

## Good to know

- 4K, HEVC and Dolby Vision channels need a device that can decode them, such as a 4K Fire TV stick or a recent phone. On other devices Relay says why a channel won't play.
- Event and PPV channels only stream while the event is on.

## About this repository

This repository holds signed release builds only. Every release is signed with the same key, so updates install over the previous version. The source code is private.
