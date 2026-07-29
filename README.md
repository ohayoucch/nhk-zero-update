# NHK Zero Update Channel

Public binary update channel for **NHK Zero**.

This repository intentionally contains only signed APK packages and release metadata. The application source code is maintained separately and is not published here.

## Channels

- `latest.json` — legacy TV metadata for clients up to v1.79.
- `tv/latest.json` — independent Android TV update channel.
- `mobile/latest.json` — independent Android Mobile update channel.
- `NHK-Zero-vX.Y.apk` / `mobile/NHK-Zero-Mobile-vX.Y.Z.apk` — signed APKs mirrored through jsDelivr.
- GitHub Releases — canonical downloadable APK assets.

Every APK is verified by the app before installation using its SHA-256 digest, package name, version and Android signing certificate.
