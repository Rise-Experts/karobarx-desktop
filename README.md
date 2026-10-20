# KarobarX desktop app

Downloads of the **KarobarX** desktop app for Windows and macOS: the POS and
shop management system, with direct printing to receipt printers.

This repository holds **only the installers and update files**. There is no
source code here. Every release is built and published automatically.

## Download

### Windows 10 / 11

Download `KarobarX-Setup-<version>.exe` from the
[latest release](https://github.com/Rise-Experts/karobarx-desktop/releases/latest) and run it.
If Windows shows *Windows protected your PC*, click **More info → Run anyway**
(only on the first install).

### macOS (Apple silicon and Intel)

Open **Terminal** (Applications → Utilities) and paste:

```bash
curl -fsSL https://github.com/Rise-Experts/karobarx-desktop/releases/latest/download/install-mac.sh | bash
```

It downloads the right version for your Mac, checks it, installs KarobarX in
**Applications** and opens it. Run the same command again any time to reinstall.

Prefer a download? Get `KarobarX-<version>-arm64.dmg` (Apple silicon, M1 and
newer) or `KarobarX-<version>-x64.dmg` (Intel) from the latest release and drag
KarobarX into Applications. The first time, macOS says it can't check the app:
open **System Settings → Privacy & Security** and click **Open Anyway**.

## Updates

KarobarX checks for new versions by itself. When one is available it asks
**Update now** or **Later**; after the download, **Restart now** installs it
(or it installs the next time you close KarobarX). There's no need to come
back here for updates.

The other files in each release (`latest.yml`, `latest-mac.yml`, `*.blockmap`,
`*.zip`, `install-mac.sh`) are used by the installer and the automatic update. You don't need to download them.

## Help

Website: [karobarx.riseexperts.de](https://karobarx.riseexperts.de)
