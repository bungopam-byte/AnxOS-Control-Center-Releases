# AnxOS Control Center v1.7-build148 - Private Alpha Hotfix

This is a Private Alpha hotfix for invited testers only. It is not stable, production-ready, fully validated, or generally available.

Build 148 replaces build 147 because build 147 can still crash during packaged Windows startup when shared desktop modules are missing from app.asar.

Published assets are attached to the GitHub prerelease. This directory contains release metadata and checksums used by the website and validation workflow.

## Expected assets

- AnxOS-Control-Center-Setup-1.7-build148.exe
- AnxOS-Control-Center-Setup-1.7-build148.exe.blockmap
- AnxOS-Control-Center-1.7-build148-portable.exe
- AnxOS-Control-Center-1.7-build148.AppImage
- AnxOS-Control-Center-1.7-build148.deb
- latest.yml
- latest-linux.yml
- update-manifest.json
- SHA256SUMS

## Validation scope

Static packaging validation and artifact smoke tests passed. The packaged Windows and Linux app.asar files were inspected and contain required shared modules. Additional clean Windows real-machine validation was not completed for this Private Alpha hotfix.
