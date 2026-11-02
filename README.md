# Gira — installers

Downloads for the Gira tour-management app. The source code lives in the `Gira` repository; this repository only hosts release builds.

## macOS

Download the latest `Gira-<version>-arm64.dmg` from the **Releases** page (Apple Silicon Macs). The build is not notarized yet, so the first launch needs one extra step:

1. Open the `.dmg` and drag **Gira** to Applications.
2. Right-click **Gira** in Applications → **Open** → **Open** again. (Alternatively: `xattr -d com.apple.quarantine "/Applications/Gira.app"`.)
3. On first launch, open **Gira → Server URL…** (⌘,) and enter the address of your team's Gira server. The default is `http://localhost:3040`, which only works on a machine running the backend.

## iOS

The iOS app is distributed through TestFlight; ask the tour office for an invite.
