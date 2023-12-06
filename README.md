#### Compile customized firmware online in one minute: [openwrt.ai](https://openwrt.ai)
#### Supports 200+ devices:
X86/64, friendly NanoPi, R2S, R4S, R4SE, R5S, R2C, R5C, R6S, NEO3, Phicomm N1, K2P, K3, Raspberry Pi 4B, 3B/3B+, 2B, Electric Rhino r68s, r66s, Orange Pi R1 Plus, R1 Plus LTS, Redmi AX6, Xiaomi AX3600, Xiaomi AX9000, Redmi AX6000, Redmi AX6S/Xiaomi AX3200, Redmi AC2100, Xiaomi AC2100, Phicomm K3, 360V6, Wanke Cloud, Jirou HIWIFI HC5962 (JiRoute 4, B70), HC5661A, HC5761A, HC5861B, Xiaomi 4, Xiaomi R3G, Xiaomi R3P, newifi-d2 (New Router 3), Xiaoyu XY-C5, Jingdou Cloud 2.0 (P&W R619AC), GL.iNet GL-MT1300, GL-AX1800, GL-AXT1800, GL-microuter-N300, GL-MT300N V2, Xiaomi CR660X (CR6606/CR6608/CR6609), Xiaomi 4A Gigabit Edition, Xiaomi R3G-v2, Xiaomi Youth Edition Nano, Thunder Download timecloud, Youku yk-l2, Youhua wr1200js, Sunflower X3A, ASUS RT-ACRH17, RT-AC58u/RT-ACRH13, RT-ac85p, RT-n56u-b1, RT-AC88U, RT-AC1200, RT- AC1200 V2, NETGEAR R6220, R6260, R6120, R6700-v2, R6800, R6850, R6900-v2, R7450, wndr3700-v5, H1 Box, Shell Cloud P1, My Cloud lL Pro, x96 Max, Weijia Cloud V- Plus, Octopus Planet ZYXQ, GT-King, Odroid N2, MXQ Pro+, JD Wireless JDCloud RE-SP-01B, Linksys WRT1200AC, WRT1900AC v1, WRT1900AC v2, WRT3200ACM, WRT1900ACS v1, WRT1900ACS v2, WRT32X, EA7500 v2, etc.

[1]: https://img.shields.io/badge/license-GPLV2-brightgreen.svg
[2]: /LICENSE
[3]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
[4]: https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/pulls
[5]: https://img.shields.io/badge/Issues-welcome-brightgreen.svg
[6]: https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/issues/new
[7]: https://img.shields.io/github/v/release/hyird/Action-Openwrt
[8]: https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/releases
[10]: https://img.shields.io/badge/Contact-telegram-blue
[11]: https://t.me/opwrt
[12]: https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/actions/workflows/Openwrt-AutoBuild.yml/badge.svg
[13]: https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/actions

[![license][1]][2]
[![GitHub Stars](https://img.shields.io/github/stars/kiddin9/OpenWrt_x86-r2s-r4s.svg?style=flat-square&label=Stars)](https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/kiddin9/OpenWrt_x86-r2s-r4s.svg?style=flat-square&label=Forks)](https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/fork)
[![PRs Welcome][3]][4]
[![Issue Welcome][5]][6]
[![AutoBuild][12]][13]

<a href="https://t.me/opwrt" target="_blank">TG notification channel</a>
 ## 1. **Features**

 + Cutting edge, openwrt official openwrt-23.05 branch version, Kernel 5.15, synchronized with the latest official source code.

 + The original version is extremely pure. The firmware only includes basic Internet functions by default. Plug-ins can be installed online in the background. System upgrades will not lose plug-ins and configurations.

 + The self-built plug-in warehouse includes almost all open source plug-ins on the market. The plug-in library is updated daily, and the system automatically updates all installed plug-ins.

 + Customize exclusive firmware online through [openwrt.ai](https://openwrt.ai), no professional knowledge required, generated in one minute. It also supports github cloud compilation.

+ One-click OTA update firmware in the background, eliminating the need to find firmware, download firmware, upload firmware and other tedious operations every time the firmware is upgraded.

 + One-click setting of bypass route in the background and one-click switch on IPv6.

 + Support online installation of all Kmod kernel modules.

 + Replace Uhttpd with Nginx, support reverse proxy; WebDAV and many other methods.

 + Performance, friendliness, ease of use, plug-ins, and custom optimization for special domestic environments, etc., ready to use out of the box## 2. **Firmware**

 There are three ways to generate firmware: online customized generation, GitHub compilation, and localized compilation.

You can choose any one for firmware generation as needed.

 ### 2.1 **Online generation**

 Visit [https://openwrt.ai](https://openwrt.ai) through the browser to customize the firmware, and then download and use it directly after the firmware generation is completed.

 ### 2.2 **GitHub Compilation**

 + Fork the warehouse

 + Add relevant environment parameters REPO_TOKEN, SCKEY, TELEGRAM_CHAT_ID as needed

+ Select Repo Dispatcher on the Actions page and click Run workflow
 ### 2.3 **GitHub combined with browser plug-in compilation**
 Please install [script](https://greasyfork.org/scripts/407616-github-actions-trigger/code/Github%20Actions%20Trigger.user.js) in the browser that supports Greasyfork, and it will appear in the upper right corner of the warehouse x86_64 Actions, K2P Actions and other buttons, just click the corresponding button. More ways to play [repo-dispatcher](https://github.com/tete1030/github-repo-dispatcher)

 ## 3. **Use**

 ### 3.1 **Backstage**

 + Login address op/ or 10.0.0.1 (If the background cannot be opened, please try to plug and unplug the wan and lan network cables in sequence.)

 + Default user root

 + Default password root

 ### 3.2 **Quick Access**

### 3.2 **Quick Access**
 Some services need to be installed and enabled in the software package first. You can adjust and add more shortcuts in /etc/nginx/conf.d/shortcuts.conf.

 + op/ can open the OpenWRT background, that is, lan ip

 + ql/ can open the Qinglong backend, that is, lan ip:5700

 + adg/ can open the AdGuardHome management background, that is, lan ip:3000

 + pve/ can open Proxmox VE virtual machine management. The default is 10.0.0.10:8006

 + by/ can open the Bypass plug-in page, which is ip/luci/admin/services/bypass

 + pk/ can open the Packages plug-in management page, which is ip/luci/admin/system/opkg

+ ag/ can open the Aria2 Web panel i.e. ip/ariang

 + ug/ can open the firmware online update page, which is ip/luci/admin/services/gpsysupgrade

 ## 4. **Notes**

 + Please use a fresh installation when using it for the first time to avoid upgrade failures and other possible bugs.

 + Cloud compilation requires [here](https://github.com/settings/tokens) to create a token, then add a Secret named REPO_TOKEN in this warehouse Settings->Secrets, fill in the token value, otherwise it will not work Trigger compilation.

 + Add PPPOE_USERNAME and PPPOE_PASSWD respectively in the warehouse Settings->Secrets to set the default dial-up account password. There are [security risks](https://github.com/kiddin9/OpenWrt_x86-r2s-r4s/issues/23).

 + Add SCKEY in the warehouse Settings->Secrets to push the compilation results to WeChat through [Server Sauce](http://sc.ftqq.com).

 + Add TELEGRAM_CHAT_ID and TELEGRAM_TOKEN in the warehouse Settings->Secrets to push the compilation results to Telegram Bot. [Tutorial](https://longnight.github.io/2018/12/12/Telegram-Bot-notifications)

+ DIY cloud compilation tutorial reference: [Read the details in my blog (in Chinese) | Chinese tutorial](https://p3terx.com/archives/build-openwrt-with-github-actions.html)


 + Default plug-ins include: Opkg package management, Bypass intelligent bypassing the wall, Samba4 file sharing (x86), UPNP automatic port forwarding, Turbo ACC network acceleration.
 Please install other plug-ins in the background -> software package by yourself. The plug-ins will not be lost during system upgrades. After each system upgrade is completed and the network is connected, all plug-ins that have been installed automatically will be installed.

 ## 5. **System screenshot display**
![](https://github.com/kiddin9/luci-theme-edge/raw/master/Screenshots/1.png)
![](https://github.com/kiddin9/luci-theme-edge/raw/master/Screenshots/3.png)
![](https://github.com/kiddin9/luci-theme-edge/raw/master/Screenshots/8.png)


------
For English

Build OpenWrt using GitHub Actions

## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/kiddin9/OpenWrt)
- click the `Star` button, and the build will starts automatically.Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.


## Acknowledgments

#### Rockchip的Kernel等部分源码来源 https://github.com/coolsnowwolf/lede
#### ipq807x的Kernel等部分源码来源 https://github.com/Boos4721/openwrt
#### ipq60xx的Kernel等部分源码来源 https://github.com/coolsnowwolf/openwrt-gl-ax1800

- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [P3TERX](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
- [aparcar](https://github.com/openwrt/asu)
- [unifreq](https://github.com/unifreq/openwrt_packit)
- [Boos4721](https://github.com/Boos4721/openwrt)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)


