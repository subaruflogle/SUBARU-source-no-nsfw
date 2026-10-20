# SUBARU customization notes

This source tree has been branded as SUBARU.

- App display name changed from Anikku to SUBARU.
- Default theme preference is now dark mode.
- Default theme palette uses a red accent with dark surfaces.
- Default launcher icon is a black/red/white S mark across legacy and adaptive launcher resources.
- Arabic translations already existed in `i18n/src/commonMain/moko-resources/ar`; these are retained.
- Existing anime extension/source infrastructure and download, library/favorites, and history functionality are retained from the upstream project.

Build command (from this directory): `./gradlew :app:assembleStandardRelease` (if this project defines the standard release task), or inspect available tasks with `./gradlew :app:tasks`.

A successful APK build and runtime/source verification are still required before distributing the APK.