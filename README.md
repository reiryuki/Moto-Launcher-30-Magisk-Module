# Moto Launcher Magisk Module

## DISCLAIMER
- Moto apps and blobs are owned by Motorola™.
- The MIT license specified here is for the Magisk Module only, not for Moto apps and blobs.

## Descriptions
Home Launcher app target SDK 30 by Motorola Mobility LLC. ported and integrated as a Magisk Module for all supported and rooted devices with Magisk

## Sources
- Launcher3QuickStep.apk https://dumps.tadiphone.dev/dumps/motorola/nio msi_prc-user-11-RRN31.Q3-1-11-1-919e2-release-keys
- libmagiskpolicy.so: Magisk (stable) 30.7 (30700)

## Changelog

v1.17
- Update libmagiskpolicy.so from Magisk (stable) 30.7 (30700)
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/

v1.16
- Fix wrong target in latest KernelSU
- Fix denial if executing default.sh

v1.15
- Fix a crash in Android 15
- Move moto-core_services.jar to Moto Core Magisk Module
- Re-fix conflict with PixelConfigOverlayCommon.apk

v1.14
- Android 15 (SDK 35) support
- Fix splitscreen
- Add Action button to clear app caches
- Fix conflict with PixelConfigOverlayCommon.apk if moto.recents=1
- Fix bug in uninstall.sh

v1.13
- Fix crashes in Android 14

## Screenshots
https://t.me/androidryukimods/294

## Requirements
- Android 9 (SDK 28) until 15 (SDK 35) only
- Magisk or Kitsune Mask or KernelSU or Apatch installed
- Moto Core Magisk Module installed https://github.com/reiryuki/Moto-Core-Magisk-Module
- Recents provider requires Android 11 (SDK 30) and up
- Gesture navigation requires android.permission.INJECT_EVENTS. The permission can only be granted in disabled Android Signature Verification in Android 13 (SDK 33) and bellow.

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install Moto Core Magisk Module first: https://github.com/reiryuki/Moto-Core-Magisk-Module
- If you want to activate the recents provider, READ Optionals bellow!
- Install this module https://devuploads.com/akdequ2a3lf8 via Magisk app or Kitsune Mask app or KernelSU app or Apatch app only
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (enable show system apps) and reboot afterwards
- Change your default home to this Moto Launcher (or you can copy the content of default.sh and paste it to Termux/Terminal Emulator app. Type su and grant root first!)

## Optionals
- https://t.me/ryukinotes/82
- Global: https://t.me/ryukinotes/35

## Troubleshootings
- https://t.me/ryukinotes/82
- Global: https://t.me/ryukinotes/34

## Known Issues
- Recents screenshot button is only working in Android 11 (SDK 30)
- Recents Edge display doesn't work

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


