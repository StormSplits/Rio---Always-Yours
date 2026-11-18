# Rio — Always Yours

This repository is reserved for Rio's Windows installer downloads, update manifests and cryptographic update signatures.

No Rio application source code is stored in this repository. Development history remains private.

## Update files

An approved published release can contain:

- `Rio_<version>_x64-setup.exe` — Windows installer
- `Rio_<version>_x64-setup.exe.sig` — Tauri updater signature
- `latest.json` — version, release notes, signature and download URL
- `SHA256SUMS.txt` — installer checksum

Rio checks `https://github.com/StormSplits/Rio---Always-Yours/releases/latest/download/latest.json` over HTTPS and verifies the installer with its embedded public key before installation. No GitHub login or token is embedded in Rio.

The development build contains GPLv3-derived components. Publication of installers remains pending a compliant distribution arrangement. Draft release files are for maintainer review and are not public updates.

© Storm Splits. Third-party rights and licenses remain with their respective owners.
