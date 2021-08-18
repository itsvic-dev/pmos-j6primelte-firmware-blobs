# j6primelte firmware blobs

## What's this repo for?
This repo contains the complete firmware blobs for j6primelte (Galaxy J6+),
more specifically Wi-Fi blobs.

## Couldn't you just use [`android_vendor_samsung-common`](https://github.com/samsung-msm8937-devs/android_vendor_samsung-common)?
Their repos, while detailed, lack the main firmware blobs actually needed by
Wi-Fi.

## Where did you find this?
The following files/folders were extracted from `NON-HLOS.bin`
from an OTA update:
- `venus.*`
- `wcnss.*`

The following files/folders were extracted from `vendor.img`
from an OTA update:
- `wlan/`

The following files/folders were extracted from `modem.img`
from an OTA update:
- `modem_pr/`
- `adsp.*`
- `modem.*`
- `mba.mbn`
