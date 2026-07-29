# NHK Zero Update Channel

Public binary update channel for **NHK Zero**.

This repository intentionally contains only signed APK packages and release metadata. The application source code is maintained separately and is not published here.

## Files

- `latest.json` — metadata consumed by the in-app updater.
- `NHK-Zero-vX.Y.apk` — signed release APK mirrored through jsDelivr.
- GitHub Releases — canonical downloadable APK assets.

Every APK is verified by the app before installation using its SHA-256 digest, package name, version and Android signing certificate.

