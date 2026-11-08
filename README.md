# MainHost Mobile releases

Public download host for the MainHost Android app (BETA). The source lives in
the private `Dyallab/mainhost` repository, under `packages/mobile`.

- Every release is an EAS build of the `preview` profile (internal distribution).
- Assets are signed by the EAS Android keystore. Each release lists its SHA-256
  and the minimum Android version.
- The app asks for login like the web. Downloading the APK grants no access.
- The APK is attached to a release, not committed to this repository.

Download the latest build: <https://github.com/Dyallab/mainhost-mobile/releases/latest>

## Install

1. Open the release on your Android phone.
2. Download the `.apk` asset and allow installs from your browser or file
   manager when Android asks.
3. Open the file, install it and sign in with your MainHost account.
