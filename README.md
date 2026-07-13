# Apkaura

The Browser for APK Users.

- **Website**: https://apkaura.app
- **Download**: https://apkaura.app/dl/apkaura-0.8.0.apk
- **Verify signature**: https://apkaura.app/verify
- **Telegram channel**: https://t.me/ApkauraApp
- **Contact**: dev@apkaura.app

Beta stage; source is closed for V1. Release notes are posted on the
Telegram channel.

## Latest release

**v0.8.0** — Beta
- Shizuku silent install now works for `.xapk` / `.apkm` / `.apks` bundles (fixed cache dir permissions so `shell` uid can read splits)
- Shizuku status updates live — no need to restart the app after starting the service or granting permission
- APKMirror `.apkm` v5 (DEFLATE + data descriptor) support on Android 16
- APKPure `.xapk` (STORED + data descriptor) support on Android 9
- Corrupted-APK attribution fixed — no longer reported as "unsigned"
- Unknown-sources permission check moved before unpack (no more double 30s wait)
- Install sheet: VT result chip always tappable, dark-mode chip legibility fixed, sensitive-permissions block hides when empty
- New onboarding: three intent cards (Explore / Install / Update) with skip always available
- Downloads empty state guides first-time users to APK sites
- Desktop-mode viewport no longer shrinks the new-tab page
- Firebase telemetry for bundle-extract failures — catches new zip-format variants without waiting for user reports
- APK size: **7.4 MB**

Signing certificate SHA-256:
`e5a6053451d4b5947ac1375f4aefccdcc3a85f2dee5f558d48fac9cdb7132cfc`

APK SHA-256:
`9b9c32585a26a87d1c8b12d766e41c1f18d62be1746a7da94f05bd2dd5abd1a2`
