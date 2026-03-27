# Tenda_vul
Tenda 路由器漏洞挖掘与验证分析记录。

## 漏洞列表

| 目录 | 产品 | 接口/功能 | 参数 | 类型 | CVE |
| --- | --- | --- | --- | --- | --- |
| [tenda-fh1202-advsetwrlsafeset-mit-ssid-buffer-overflow](tenda-fh1202-advsetwrlsafeset-mit-ssid-buffer-overflow) | FH1202 | Wrlsafeset / `formWrlsafeset` | `mit_ssid` | Buffer Overflow | CVE-2026-3807 |
| [tenda-fh1202-advsetwrlsafeset-mit-ssid-index-buffer-overflow](tenda-fh1202-advsetwrlsafeset-mit-ssid-index-buffer-overflow) | FH1202 | Wrlsafeset / `formWrlsafeset` | `mit_ssid_index` | Buffer Overflow | CVE-2026-3807 |
| [tenda-fh1202-webtypelibrary-websiteid-buffer-overflow](tenda-fh1202-webtypelibrary-websiteid-buffer-overflow) | FH1202 | WebTypeLibrary / `formWebTypeLibrary` | `webSiteId` | Buffer Overflow | CVE-2026-3808 |
| [tenda-fh1202-safeemailfilter-page-buffer-overflow](tenda-fh1202-safeemailfilter-page-buffer-overflow) | FH1202 | SafeEmailFilter / `fromSafeEmailFilter` | `page` | Buffer Overflow | CVE-2023-38932(duplicate) |
| [tenda-fh1202-natsaticsetting-page-buffer-overflow](tenda-fh1202-natsaticsetting-page-buffer-overflow) | FH1202 | NatSaticSetting / `fromNatStaticSetting` | `page` | Buffer Overflow | CVE-2026-3809 |
| [tenda-fh1202-dhcplistclient-page-buffer-overflow](tenda-fh1202-dhcplistclient-page-buffer-overflow) | FH1202 | DhcpListClient / `fromDhcpListClient` | `page` | Buffer Overflow | CVE-2026-3810 |
| [tenda-fh1202-p2plistfilter-page-buffer-overflow](tenda-fh1202-p2plistfilter-page-buffer-overflow) | FH1202 | P2pListFilter / `fromP2pListFilter` | `page` | Buffer Overflow | CVE-2026-3811 |
| [tenda-i3-setcfm-funcpara1-buffer-overflow](tenda-i3-setcfm-funcpara1-buffer-overflow) | i3 | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow | CVE-2026-3799 |
| [tenda-i3-setautoping-ping1-buffer-overflow](tenda-i3-setautoping-ping1-buffer-overflow) | i3 | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow | CVE-2026-3801 |
| [tenda-i3-setautoping-ping2-buffer-overflow](tenda-i3-setautoping-ping2-buffer-overflow) | i3 | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow | CVE-2026-3801 |
| [tenda-i3-formexeCommand-cmdinput-buffer-overflow](tenda-i3-formexeCommand-cmdinput-buffer-overflow) | i3 | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow | CVE-2026-3802 |
| [tenda-i3-formWifiMacFilterGet-index-buffer-overflow](tenda-i3-formWifiMacFilterGet-index-buffer-overflow) | i3 | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow | CVE-2026-3803 |
| [tenda-i3-formWifiMacFilterSet-index-buffer-overflow](tenda-i3-formWifiMacFilterSet-index-buffer-overflow) | i3 | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow | CVE-2026-3804 |
| [tenda-i3-formWifiMacFilterSet-go-buffer-overflow](tenda-i3-formWifiMacFilterSet-go-buffer-overflow) | i3 | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow | CVE-2026-3804 |
| [tenda-i3-formwrlSSIDget-index-buffer-overflow](tenda-i3-formwrlSSIDget-index-buffer-overflow) | i3 | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow | CVE-2026-3970 |
| [tenda-i3-formwrlSSIDset-index-buffer-overflow](tenda-i3-formwrlSSIDset-index-buffer-overflow) | i3 | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow | CVE-2026-3971 |
| [tenda-i3-formwrlSSIDset-go-buffer-overflow](tenda-i3-formwrlSSIDset-go-buffer-overflow) | i3 | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow | CVE-2026-3971 |
| [tenda-w3-setcfm-funcpara1-buffer-overflow](tenda-w3-setcfm-funcpara1-buffer-overflow) | w3 | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow | CVE-2026-3972 |
| [tenda-w3-setautoping-ping1-buffer-overflow](tenda-w3-setautoping-ping1-buffer-overflow) | w3 | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow | CVE-2026-3973 |
| [tenda-w3-setautoping-ping2-buffer-overflow](tenda-w3-setautoping-ping2-buffer-overflow) | w3 | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow | CVE-2026-3973 |
| [tenda-w3-formexeCommand-cmdinput-buffer-overflow](tenda-w3-formexeCommand-cmdinput-buffer-overflow) | w3 | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow | CVE-2026-3974 |
| [tenda-w3-formWifiMacFilterGet-index-buffer-overflow](tenda-w3-formWifiMacFilterGet-index-buffer-overflow) | w3 | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow | CVE-2026-3975 |
| [tenda-w3-formWifiMacFilterSet-index-buffer-overflow](tenda-w3-formWifiMacFilterSet-index-buffer-overflow) | w3 | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow | CVE-2026-3976 |
| [tenda-w3-formWifiMacFilterSet-go-buffer-overflow](tenda-w3-formWifiMacFilterSet-go-buffer-overflow) | w3 | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow | CVE-2026-3976 |
| [tenda-w3-formwrlSSIDget-index-buffer-overflow](tenda-w3-formwrlSSIDget-index-buffer-overflow) | w3 | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow | CVE-2026-4007 |
| [tenda-w3-formwrlSSIDset-index-buffer-overflow](tenda-w3-formwrlSSIDset-index-buffer-overflow) | w3 | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow | CVE-2026-4008 |
| [tenda-w3-formwrlSSIDset-go-buffer-overflow](tenda-w3-formwrlSSIDset-go-buffer-overflow) | w3 | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow | CVE-2026-4008 |
| [tenda-i3-v1.0.0.7(3856)-setcfm-funcpara1-buffer-overflow](tenda-i3-v1.0.0.7(3856)-setcfm-funcpara1-buffer-overflow) | i3 V1.0.0.7(3856) | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-setautoping-ping1-buffer-overflow](tenda-i3-v1.0.0.7(3856)-setautoping-ping1-buffer-overflow) | i3 V1.0.0.7(3856) | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-setautoping-ping2-buffer-overflow](tenda-i3-v1.0.0.7(3856)-setautoping-ping2-buffer-overflow) | i3 V1.0.0.7(3856) | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-formexeCommand-cmdinput-buffer-overflow](tenda-i3-v1.0.0.7(3856)-formexeCommand-cmdinput-buffer-overflow) | i3 V1.0.0.7(3856) | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-formWifiMacFilterGet-index-buffer-overflow](tenda-i3-v1.0.0.7(3856)-formWifiMacFilterGet-index-buffer-overflow) | i3 V1.0.0.7(3856) | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-formWifiMacFilterSet-index-buffer-overflow](tenda-i3-v1.0.0.7(3856)-formWifiMacFilterSet-index-buffer-overflow) | i3 V1.0.0.7(3856) | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-formWifiMacFilterSet-go-buffer-overflow](tenda-i3-v1.0.0.7(3856)-formWifiMacFilterSet-go-buffer-overflow) | i3 V1.0.0.7(3856) | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-formwrlSSIDget-index-buffer-overflow](tenda-i3-v1.0.0.7(3856)-formwrlSSIDget-index-buffer-overflow) | i3 V1.0.0.7(3856) | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-formwrlSSIDset-index-buffer-overflow](tenda-i3-v1.0.0.7(3856)-formwrlSSIDset-index-buffer-overflow) | i3 V1.0.0.7(3856) | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow | TBD |
| [tenda-i3-v1.0.0.7(3856)-formwrlSSIDset-go-buffer-overflow](tenda-i3-v1.0.0.7(3856)-formwrlSSIDset-go-buffer-overflow) | i3 V1.0.0.7(3856) | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-setcfm-funcpara1-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-setcfm-funcpara1-buffer-overflow) | w3 V1.0.0.4(3822)_EN | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-setautoping-ping1-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-setautoping-ping1-buffer-overflow) | w3 V1.0.0.4(3822)_EN | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-setautoping-ping2-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-setautoping-ping2-buffer-overflow) | w3 V1.0.0.4(3822)_EN | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-formexeCommand-cmdinput-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-formexeCommand-cmdinput-buffer-overflow) | w3 V1.0.0.4(3822)_EN | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-formWifiMacFilterGet-index-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-formWifiMacFilterGet-index-buffer-overflow) | w3 V1.0.0.4(3822)_EN | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-formWifiMacFilterSet-index-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-formWifiMacFilterSet-index-buffer-overflow) | w3 V1.0.0.4(3822)_EN | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-formWifiMacFilterSet-go-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-formWifiMacFilterSet-go-buffer-overflow) | w3 V1.0.0.4(3822)_EN | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-formwrlSSIDget-index-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-formwrlSSIDget-index-buffer-overflow) | w3 V1.0.0.4(3822)_EN | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-formwrlSSIDset-index-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-formwrlSSIDset-index-buffer-overflow) | w3 V1.0.0.4(3822)_EN | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow | TBD |
| [tenda-w3-v1.0.0.4(3822)_EN-formwrlSSIDset-go-buffer-overflow](tenda-w3-v1.0.0.4(3822)_EN-formwrlSSIDset-go-buffer-overflow) | w3 V1.0.0.4(3822)_EN | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow | TBD |
