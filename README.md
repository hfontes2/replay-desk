# Replay Desk for Android

The Replay Desk web build (`www/`) wrapped as an Android app with Capacitor.
Every push to `main` builds a debug APK on GitHub Actions and puts it on the `apk` branch
(`ReplayDesk.apk`) and on the run's downloads.

- Works offline: the market data (EURUSD and GBPUSD, M1, 2023-2024) is inside the app.
- Projects, trades and drawings are saved on the phone, separate from the claude.ai version.
- Export / Copy in the trades panel (and Export all trades on the projects page) share the trades as a CSV through Android's share sheet.
- Install: download the APK on the phone and open it; Android asks to allow installing from that app once.

To update the app, replace `www/` with a new web build and push.
