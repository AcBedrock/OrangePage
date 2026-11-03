# Third-party software

The OrangePage application sources are MIT licensed. The following unmodified components retain their own licenses. No service account, cloud database, telemetry account, or developer credential is bundled.

## Syncthing 2.1.7 (MPL-2.0)

The Windows distribution bundles the official `syncthing-windows-amd64-v2.1.7` release, including its LICENSE and AUTHORS files. Copyright belongs to the Syncthing Authors. Corresponding source: <https://github.com/syncthing/syncthing/tree/v2.1.7>; source archive: <https://github.com/syncthing/syncthing/archive/refs/tags/v2.1.7.tar.gz>.

The Android distribution contains the unmodified ARM64 `libsyncthingnative.so` from Syncthing-Fork v2.1.7.0. Corresponding wrapper/build source: <https://github.com/researchxxl/syncthing-android/tree/v2.1.7.0>. Its pinned Syncthing source/submodule and build instructions are in that tag. Original artifact and SHA256 are recorded in `android/build.ps1`. The wrapper project is MPL-2.0. OrangePage does not include its UI or proprietary branding.

MPL text: <https://www.mozilla.org/MPL/2.0/>; a copy is supplied in `licenses/MPL-2.0.txt`. Source code for these covered components remains available at the linked exact versions. Preserve this notice when redistributing.

## Electron 45.2.1 (MIT, plus Chromium and other component licenses)

Windows embeds Electron. Its LICENSE and LICENSES.chromium.html are supplied in the Electron subfolder beside this notice. Source: <https://github.com/electron/electron/tree/v45.2.1>. Electron's internal components retain the notices in LICENSES.chromium.html.

## Build tools (not installed as application dependencies)

Android builds use Eclipse Temurin OpenJDK 17 (GPLv2 with Classpath Exception) and Google Android SDK Build Tools. Their downloaded archives retain upstream licenses; they are not included in the source archive or application. Windows packaging uses @electron/packager (BSD-2-Clause). Build-only dependencies and their licenses remain in the pinned package lock and installed dependency directories.
