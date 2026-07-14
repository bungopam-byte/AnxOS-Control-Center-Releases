# AnxOS Control Center v1.7-build149 - Private Alpha Hotfix

This is a Private Alpha hotfix for invited testers only. It is not stable, production-ready, fully validated, or generally available.

Build 149 replaces build 148 because build 148 can launch but the packaged Marketplace catalog can be empty when required config files are missing from app.asar. Build 149 also fixes the CurseForge connection test path that could show a generic AGENT_HTTP_ERROR instead of the selected Agent's structured provider diagnostic result.

Published assets are attached to the GitHub prerelease. This directory contains release metadata and checksums used by the website and validation workflow.

## Expected assets

- AnxOS-Control-Center-Setup-1.7-build149.exe
- AnxOS-Control-Center-Setup-1.7-build149.exe.blockmap
- AnxOS-Control-Center-1.7-build149-portable.exe
- AnxOS-Control-Center-1.7-build149.AppImage
- AnxOS-Control-Center-1.7-build149.deb
- latest.yml
- latest-linux.yml
- update-manifest.json
- SHA256SUMS

## Validation scope

Static packaging validation and artifact smoke tests passed. The packaged Windows and Linux app.asar files were inspected and contain required shared modules, Local Agent metadata, and Marketplace config files. CurseForge packaged regression checks passed. Additional clean Windows real-machine validation was not completed for this Private Alpha hotfix.
