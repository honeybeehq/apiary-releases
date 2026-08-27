# Apiary releases

Public release host for the Apiary desktop app (`honeybeehq/apiary`).
Each release carries the notarized `Apiary-<version>-arm64.dmg`, the `.zip` +
blockmap used by in-app updates, `latest-mac.yml`, and `SHA256SUMS`.

Source lives in the private product repo; this repository only exists so
`electron-updater` and the install script can fetch artifacts unauthenticated.
