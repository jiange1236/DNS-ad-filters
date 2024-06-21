# 简介

本项目生成适用于 [**Smartdns**] 的DNS屏蔽广告规则集（DOMAIN-SET）。使用 GitHub Actions 北京时间每天早上 6:40 自动构建，保证规则最新。

## 说明

本项目规则集（DOMAIN-SET）的数据主要来源于项目 [@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) 和 [@v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)；[`Apple`](https://github.com/jiange1236/smartdns-rules/blob/release/Loyalsoldier/apple-cn.txt) 和 [`Google`](https://github.com/jiange1236/smartdns-rules/blob/release/Loyalsoldier/google-cn.txt) 列表里的部分域名来源于项目 [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)；中国大陆 IPv4 地址数据使用 [@17mon/china_ip_list](https://github.com/17mon/china_ip_list)。

## 规则文件地址及使用方式

### 在线地址（URL）

> 如果无法访问域名 `raw.githubusercontent.com`，可以使用第二个地址（`cdn.jsdelivr.net`），但是内容更新会有 12 小时的延迟。

#### 217heidai
- **屏蔽域名列表 adblockdns.txt**：
  - [https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/217heidai/adblockdns.txt](https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/217heidai/adblockdns.txt)
  - [https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/217heidai/adblockdns.txt](https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/217heidai/adblockdns.txt)
- **白名单域名列表 proxy-list.txt**：
  - [https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/217heidai/adblockdns-whitelist.txt](https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/217heidai/adblockdns-whitelist.txt)
  - [https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/217heidai/adblockdns-whitelist.txt](https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/217heidai/adblockdns-whitelist.txt)
#### AdGuard
- **屏蔽域名列表 dnsfilter.txt**：
  - [https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/AdGuard/dnsfilter.txt](https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/AdGuard/dnsfilter.txt)
  - [https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/AdGuard/dnsfilter.txt](https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/AdGuard/dnsfilter.txt)
- **白名单域名列表 dnsfilter-whitelist.txt**：
  - [https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/AdGuard/dnsfilter-whitelist.txt](https://raw.githubusercontent.com/jiange1236/DNS-ad-filters/release/AdGuard/dnsfilter-whitelist.txt)
  - [https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/AdGuard/dnsfilter-whitelist.txt](https://cdn.jsdelivr.net/gh/jiange1236/DNS-ad-filters@release/AdGuard/dnsfilter-whitelist.txt)

### 使用方式

关于 Smartdns 的详细使用方法，见[官方手册](https://pymumu.github.io/smartdns)。


## 致谢

- [@Loyalsoldier/surge-rules](https://github.com/Loyalsoldier/surge-rules)
- [@Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)
- [@Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)
- [@v2fly/domain-list-community](https://github.com/v2fly/domain-list-community)
- [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
- [@17mon/china_ip_list](https://github.com/17mon/china_ip_list)
- [@jklolixxs/SmartDNS_Rule](https://github.com/jklolixxs/SmartDNS_Rule)

## 项目 Star 数增长趋势

[![Stargazers over time](https://starchart.cc/jiange1236/DNS-ad-filters.svg)](https://starchart.cc/jiange1236/DNS-ad-filters)
