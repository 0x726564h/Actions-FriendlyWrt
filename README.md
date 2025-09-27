# Build FriendlyWrt using GitHub Actions [![.github/workflows/build.yml](https://github.com/0x726564h/Actions-FriendlyWrt/actions/workflows/build.yml/badge.svg)](https://github.com/0x726564h/Actions-FriendlyWrt/actions/workflows/build.yml)

[English](README_en.md)

### Basic Information
- Username: root  
- Password: password  
- Backend IP: 192.168.2.1  
- Firmware download: https://github.com/friendlyarm/Actions-FriendlyWrt/releases  
- More usage instructions: https://wiki.friendlyelec.com/wiki/index.php/Template:FriendlyWrt21/zh  

### Firmware Notes
- This build is **only for NanoPi R2S**.  
- Additional packages included:  
  - **AmneziaVPN** (https://github.com/amnezia-vpn/amneziawg-openwrt.git) 
    - kmod-amneziawg
    - amneziawg-tools
    - luci-proto-amneziawg
  - **PassWall** (https://github.com/xiaorouji/openwrt-passwall-packages.git)
    - luci-app-passwall
    - luci-i18n-passwall-zh-cn
    - chinadns-ng
    - dns2socks
    - geoview
    - hysteria
    - ipt2socks
    - microsocks
    - naiveproxy
    - shadow-tls
    - shadowsocks-libev
    - shadowsocksr-libev
    - simple-obfs
    - sing-box
    - tcping
    - trojan-plus
    - tuic-client
    - v2ray-plugin
    - xray-core
    - xray-plugin
- The same firmware file supports installation on both SD and eMMC, no distinction needed.  

### How to Write Firmware to eMMC
- First, write the firmware to an SD card.  
- Boot the system from the SD card.  
- Access the FriendlyWrt backend page, go to **System → eMMC Flash Assistant**, upload the firmware file directly (no need to unzip).  
- Once the flashing process is complete, remove the SD card.  
- The device will reboot automatically and boot from eMMC.  

### Update Log
*(same as original, unchanged)*

### Thanks
- [luci-app-diskman](https://github.com/lisaac/luci-app-diskman)  
- [luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)  
- [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)  
- [NanoPi-R1S-Build-By-Actions](https://github.com/skytotwo/NanoPi-R1S-Build-By-Actions)  
- [QiuSimons](https://github.com/QiuSimons/YAOF)  
