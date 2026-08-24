# CoderPad for macOS — Releases

Public distribution artifacts for the **CoderPad macOS** app: Developer-ID signed,
notarized `.dmg` builds and the Sparkle `appcast.xml` update feed.

The app's source lives in a separate **private** repository. This repo holds only
built, signed, notarized artifacts so the in-app updater (Sparkle) can fetch the
appcast and downloads over plain HTTPS without authentication.

- **Update feed:** `https://github.com/adamtheturtle/coderpad-macos-releases/releases/latest/download/appcast.xml`
- Each release attaches `coderpad-<tag>.dmg` + `appcast.xml`.
## Security

See [SECURITY.md](SECURITY.md) for vulnerability reporting.
