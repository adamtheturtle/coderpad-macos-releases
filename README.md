# CoderPad for macOS — Releases

Public distribution artifacts for the **CoderPad macOS** app: Developer-ID signed, notarized `.dmg` builds and the Sparkle `appcast.xml` update feed.

A separate **private** repository stores the app's source.
This repository publishes the signed, notarized builds and appcast.
The in-app updater (Sparkle) fetches them over public HTTPS.

- **Update feed:** `https://github.com/adamtheturtle/coderpad-macos-releases/releases/latest/download/appcast.xml`
- Each release attaches `coderpad-<tag>.dmg` + `appcast.xml`.
## Security

See [SECURITY.md](SECURITY.md) for vulnerability reporting.
