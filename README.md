# Parcel: downloads

Send files directly between people. No account, no domain, no server in the middle.

This repository holds the **download files for Parcel**. The source code is not published.

## Download

Get the latest version for your system from the
[**Releases** page](../../releases/latest).

| System | File |
| --- | --- |
| Windows | `Parcel-windows-amd64.zip` |
| macOS (Apple silicon) | `Parcel-macos-arm64.zip` |
| macOS (Intel) | `Parcel-macos-amd64.zip` |
| Linux | `Parcel-linux-amd64.zip` |

Unzip it and run Parcel. Early builds are **not code-signed yet**, so Windows may show a
SmartScreen warning ("More info", then "Run anyway") and macOS may require you to
right-click the app and choose Open the first time. Linux needs GTK 4 and WebKitGTK 6
installed (`libgtk-4-1`, `libwebkitgtk-6.0-4`).

## How it works

- **Receive:** open Parcel, press **Start receiving**, then **Copy** and send that address
  to the sender. Treat it like a password: anyone who has it can send you files until the
  session ends. Files save automatically to your save folder, and existing files are never
  overwritten.
- **Send:** switch to **Send**, drop in files or folders, and paste the address. Sending
  starts as soon as you have files and a valid address.
- Both sides see live progress, and either side can pause, resume or cancel.
- Closing the window keeps Parcel running in the tray, still receiving.

## Built on tailcat

Parcel is made possible by [**tailcat**](https://github.com/tailscale/tailcat), an
open-source project from Tailscale (BSD-3-Clause) that provides an encrypted,
NAT-traversing connection between two devices with no account or server of our own.
Without tailcat, Parcel would not exist, and we are grateful to its authors.

Parcel is an independent product and is not affiliated with or endorsed by Tailscale.
Licences for tailcat and the other components Parcel includes are in
[THIRD_PARTY_LICENSES](THIRD_PARTY_LICENSES).

## Licence

Copyright (c) 2026 Lachlan Scott (LS Media). All rights reserved. See [LICENSE](LICENSE).
