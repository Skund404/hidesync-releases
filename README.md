# HideSync Releases

Public **release feed** for the HideSync desktop app. This repo holds **only build
artifacts** — Windows installers (`.exe`), Linux `AppImage`s, and the
`electron-updater` feed files (`latest.yml` / `latest-linux.yml`). 

**No source code lives here.** HideSync source is private; this repo exists so the
installed app can read its update feed anonymously (no token shipped in the binary).

Releases are published automatically by the tag-triggered CI in the source repo
(`.github/workflows/release.yml`). To install or update HideSync, grab the latest
installer from the [Releases](../../releases) page — or just let the app update itself.
