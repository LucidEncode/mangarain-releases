# Manga Rain — release channel

Public delivery channel for the **Manga Rain** Android app. Holds only the
release manifest (`latest.json`) and APK binaries attached to Releases.

The app's source lives in a separate private repository. This repo exists so
the in-app wireless updater can read `latest.json` and download new builds
without authentication.

`latest.json` fields: `version` (display), `versionCode` (monotonic build
number the app compares against), `notes`, `apkUrl`, `sizeMb`.
