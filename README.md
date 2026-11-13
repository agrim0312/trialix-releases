# Trialix releases

Hosts the direct-download builds and the Sparkle auto-update feed for **Trialix**
(the macOS app that mirrors, controls and AI-tests a USB-connected iPhone).

- `appcast.xml` — the Sparkle update feed (the app's `SUFeedURL` points here)
- `Trialix.zip` — the notarized app, attached to each GitHub Release

Produced by `scripts/release.sh` + `scripts/appcast.sh` in the Trialix source repo.
