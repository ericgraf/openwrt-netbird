Forked from https://github.com/messense/openwrt-netbird
---

# openwrt-netbird

[![CI](https://github.com/ericgraf/openwrt-netbird/actions/workflows/CI.yml/badge.svg)](https://github.com/ericgraf/openwrt-netbird/actions/workflows/CI.yml)

OpenWrt package for [netbird](https://github.com/netbirdio/netbird)

## Usage

After installing the package, login the peer with setup key:

```bash
netbird login --setup-key <SETUP_KEY>
```

Start the netbird background service then you're good to go:

```bash
/etc/init.d/netbird enable
/etc/init.d/netbird start
```
