# Rio — Always Yours

This repository provides Rio's Windows installer downloads, update manifests and cryptographic update signatures.

No Rio application source code is stored in this repository. Development history remains private.

[Download the latest Rio installer](https://github.com/StormSplits/Rio---Always-Yours/releases/latest). Existing users can open Settings > About > Check for updates. Installation lets you choose a folder; updates retain your existing Rio profile.

## Update files

An approved published release can contain:

- `Rio_<version>_x64-setup.exe` — Windows installer
- `Rio_<version>_x64-setup.exe.sig` — Tauri updater signature
- `latest.json` — version, release notes, signature and download URL
- `SHA256SUMS.txt` — installer checksum

Rio checks `https://github.com/StormSplits/Rio---Always-Yours/releases/latest/download/latest.json` over HTTPS and verifies the installer with its embedded public key before installation. No GitHub login or token is embedded in Rio.

Rio contains GPLv3-derived components and retains third-party license notices in its installation. Keeping the development repository private does not change those license obligations. Draft releases do not serve public updates.

© Storm Splits. Third-party rights and licenses remain with their respective owners.
