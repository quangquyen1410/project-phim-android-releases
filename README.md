# Project Phim Android Releases

This public repository contains signed Android APK releases and matching update manifests for Project Phim. Application source remains in the private repository.

Download only stable releases from this repository. APKs must retain the trusted application signing certificate so Android can update existing installations. Each release includes the APK and its matching `update.json` manifest.

**First release (v0.2.0):** this release starts a new signing identity. Devices with the previous v0.1.9 app must uninstall it and manually install v0.2.0; uninstalling may erase local app data. After v0.2.0 is installed, later releases can update in place.
