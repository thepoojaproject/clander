# Minimal Calendar — Android APK

A mobile-friendly, offline calendar wrapped with Capacitor.

## GitHub → APK

1. Upload all files in this folder to a GitHub repository.
2. Push to `main` (or `master`).
3. Open **Actions** in GitHub.
4. Run **Build Android APK** (or wait for the push workflow).
5. Open the completed workflow run.
6. Download the **minimal-calendar-debug-apk** artifact.

The APK is generated automatically by GitHub Actions.

## LocalStorage
Notes are saved locally on the device/browser for each selected date.

## Project
- `index.html` — app UI
- `manifest.json` — PWA metadata
- `sw.js` — offline caching
- `capacitor.config.json` — Android wrapper configuration
- `.github/workflows/build-apk.yml` — automatic APK build
