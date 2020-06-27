# nvpnmgr
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/50f9c2244ef74cefb3da37448dd69848)](https://www.codacy.com/manual/jackyaz/nvpnmgr?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=jackyaz/nvpnmgr&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.com/jackyaz/nvpnmgr.svg?branch=master)](https://travis-ci.com/jackyaz/nvpnmgr)

## v0.9.9
### Updated on 2020-06-22
## About
The concept for this script was originally developed by [@h0me5k1n](https://github.com/h0me5k1n/asusmerlin-nvpnmgr)

Manage and update VPN Client configurations for NordVPN on AsusWRT-Merlin.

A NordVPN account is required to establish a connection.

![Menu UI](https://puu.sh/FZhMO/6ce55ca358.png)

![Web UI](https://puu.sh/FZhMt/2b17558b53.png)

## Supported firmware versions
You must be running firmware Merlin 384.15/384.13_4 or Fork 43E5 (or later) [Asuswrt-Merlin](https://asuswrt.lostrealm.ca/)

## Installation
Using your preferred SSH client/terminal, copy and paste the following command, then press Enter:

```sh
/usr/sbin/curl --retry 3 "https://raw.githubusercontent.com/jackyaz/nvpnmgr/master/nvpnmgr.sh" -o "/jffs/scripts/nvpnmgr" && chmod 0755 /jffs/scripts/nvpnmgr && /jffs/scripts/nvpnmgr install
```

## Usage
To launch the nvpnmgr menu after installation, use:
```sh
nvpnmgr
```

If this does not work, you will need to use the full path:
```sh
/jffs/scripts/nvpnmgr
```

## Updating
Launch nvpnmgr and select option u

## Help
Please post about any issues and problems here: [nvpnmgr on SNBForums]()

## FAQs
### I haven't used scripts before on AsusWRT-Merlin
If this is the first time you are using scripts, don't panic! In your router's WebUI, go to the Administration area of the left menu, and then the System tab. Set Enable JFFS custom scripts and configs to Yes.

Further reading about scripts is available here: [AsusWRT-Merlin User-scripts](https://github.com/RMerl/asuswrt-merlin/wiki/User-scripts)

![WebUI enable scripts](https://puu.sh/A3wnG/00a43283ed.png)
