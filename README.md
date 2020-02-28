# 自动发布 NanoPi-R2S 固件

> 每天定时自动编译和发布，手动修改文件也会发布新版本

请前往 [Release 页面](https://github.com/maxming2333/NanoPi-R2S/releases) 下载

![NanoPi-R2S RK3328 OpenWrt 19.07 Build For Lean](https://github.com/maxming2333/NanoPi-R2S/workflows/NanoPi-R2S%20RK3328%20OpenWrt%2019.07%20Build%20For%20Lean/badge.svg)
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/maxming2333/NanoPi-R2S?include_prereleases)
![GitHub All Releases](https://img.shields.io/github/downloads/maxming2333/NanoPi-R2S/total)


## 说明
* IP: 192.168.50.1
* 密码: password

## 特色
* 支持 RTL8821CU 芯片的 USB WiFi 设备，已知支持列表：
    - [COMFAST 726B](https://u.jd.com/DOkkhX)
    - [COMFAST CF-759BF](https://u.jd.com/C2ivH7)
* 集成 [tty228/luci-app-serverchan](https://github.com/tty228/luci-app-serverchan)
* 集成 [vernesong/OpenClash](https://github.com/vernesong/OpenClash) 及其 clash bin
* 集成 [rufengsuixing/luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome)
* 更新 [jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
* 集成 [coolsnowwolf/packages](https://github.com/coolsnowwolf/packages) 与 [coolsnowwolf/luci](https://github.com/coolsnowwolf/luci)
* 集成最新实时监控 Netdata v1.20.0

## 用法
- 修改 [`.github/workflows/r2s_lean.yml`](.github/workflows/r2s_lean.yml) 或 [`config`](config) 即可触发编译
- 每天 `09:10` 自动触发每日编译

## 注意
产品发布初期，官方代码每天都在变，遇到无法编译时，请过来查看 `.yml` 与 `config` 最新异动。

## 参考
* [使用Github的Actions功能在线编译NanoPi-R1S固件（包含H5和H3）](https://totoro.site/index.php/archives/70/)
* [skytotwo/NanoPi-R1S-Build-By-Actions](https://github.com/skytotwo/NanoPi-R1S-Build-By-Actions)
* [klever1988/nanopi-openwrt](https://github.com/klever1988/nanopi-openwrt)
* [yangliu/NanoPi-R2S](https://github.com/yangliu/NanoPi-R2S)
* [soffchen/NanoPi-R2S](https://github.com/soffchen/NanoPi-R2S)
