# Metin2 Android Downloads

Public release assets for original Metin2 Android builds. The source repository remains private.

## S24 Ultra — Tailnet server-picker QA v75

**[Download the S24 Ultra QA APK](https://github.com/ferypotter/Metin2-Downloads/releases/download/s24-qa-v75/Metin2-Tailnet-ServerPicker-QA-v75.apk)**

- Version: `0.75-tailnet-qa-updater-isolated` (versionCode `75`)
- Android package: `com.metin2.bgfx.qa` — separately installed, does **not** replace the production app.
- Android ABI: `arm64-v8a` (compatible target for Samsung Galaxy S24 Ultra).
- Size: **102,607,999 bytes**
- SHA-256: `b5f90cf226e2fa9de1e88a515e62715d7b1602b2615353174914ec93d3332184`
- Shows the FreeBSD and NAS Tailscale server choices in the original game's login UI. The phone must have Tailscale enabled in the same Tailnet to access the server directory and game TCP ports.
- **QA release only:** actual Samsung S24 game login and full world rendering remain unverified.

The production APK is distributed separately as **[Metin2 latest](https://github.com/ferypotter/Metin2-Downloads/releases/tag/apk-latest)**. Never replace its tag or binary with QA test builds.
