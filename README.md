# Mirai Super Intelligence · releases

Installers of the desktop app and the `latest.json` its in-app updater reads:
`https://github.com/Data-Mirai/mirai-releases/releases/latest/download/latest.json`.

Each release `vX.Y.Z` is drafted by the `si-desktop-release` workflow of `Data-Mirai/mirai-company` (macOS arm64 + x64 `.dmg`, Windows `-setup.exe`, Linux `.deb` + `.AppImage`, with their updater artifacts and minisign signatures). The source, the changelog and the issues live in `mirai-company`.

Rollback: mark the previous release as the latest one; installed apps never downgrade.
