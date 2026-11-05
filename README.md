# GarageBand — blank PS4 homebrew

This repository is configured to build a blank PS4 homebrew PKG through GitHub Actions using OpenOrbis v0.5.4.

- Home-screen title: `GarageBand`
- Title ID: `GBND00001`
- Content ID: `IV0000-GBND00001_00-GARAGEBAND000001`
- App body: intentionally blank; process remains open until closed from the PS4 system menu.
- Icon: fetched during the build from Apple's App Store lookup record for GarageBand (not generated).

## Build
Upload the contents of this folder to a new GitHub repository. The workflow starts automatically after the first push. You can also start it manually from the repository's Actions tab using **Build GarageBand PKG**.

When successful, open the workflow run, scroll to **Artifacts**, and download `GarageBand-PS4-PKG`. It contains the `.pkg` and `eboot.bin`.

This is an unofficial homebrew placeholder. GarageBand and its icon are Apple trademarks and this project is not affiliated with Apple.
