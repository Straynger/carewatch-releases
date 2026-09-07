# CareWatch downloads

CareWatch is a consent-led, local-first desktop app for body/pose monitoring, with a separately paired Android companion. Observations require human review. It is not a medical diagnosis, fall classifier, emergency-response replacement, or proof that food or medication was consumed.

## Download CareWatch 0.3.1

| App | Download | Build status |
|---|---|---|
| Windows x64 installer | [CareWatch Setup.exe](https://github.com/Straynger/carewatch-releases/releases/download/v0.3.1/CareWatch-Setup-0.3.1-x64.exe) | Unsigned test build |
| Windows x64 portable | [CareWatch Portable.exe](https://github.com/Straynger/carewatch-releases/releases/download/v0.3.1/CareWatch-Portable-0.3.1-x64.exe) | Unsigned test build |
| Android 8+ companion | [CareWatch.apk](https://github.com/Straynger/carewatch-releases/releases/download/v0.3.1/CareWatch-Android-debug-0.3.1.apk) | Debug-signed test build |

[Release notes and SHA-256 hashes](https://github.com/Straynger/carewatch-releases/releases/tag/v0.3.1). The Android app pairs with an approved CareWatch desktop; it is not a standalone camera analyzer or a Play Store release. Windows may show an unknown-publisher warning. Verify the file hash; no trusted-publisher signing is claimed.

47 automated checks and controlled local video/stream fixtures pass. Household cameras, physical phones, target hardware and away-from-home connectivity still require supervised acceptance. No iOS, macOS or Linux download is available.

CareWatch keeps camera analysis local. Sources and remote sharing require explicit setup and approval. Phone access uses individual, revocable pairing credentials; remote video is opt-in. Private-network installation and enrollment are separate steps, not automatic router configuration.

## About this repository

This public repository contains release-page text only; its release assets are only the `.exe` and `.apk` downloads above. Application source history, internal reports, development files, configuration, credentials and private test data are not stored here. Necessary runtime code is bundled inside the runnable apps and can be reverse engineered. Any GitHub-generated repository archive contains only page text, **not the CareWatch application or its source repository**.
