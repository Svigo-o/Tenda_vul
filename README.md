# Tenda_vul
Tenda 路由器漏洞复现与分析记录。

## 漏洞列表

| 目录 | 产品 | 接口/功能 | 参数 | 类型 | CVE |
| --- | --- | --- | --- | --- | --- |
| [tenda-fh1202-advsetwrlsafeset-mit-ssid-buffer-overflow](tenda-fh1202-advsetwrlsafeset-mit-ssid-buffer-overflow) | FH1202 | Wrlsafeset / `formWrlsafeset` | `mit_ssid` | Buffer Overflow | TBD |
| [tenda-fh1202-advsetwrlsafeset-mit-ssid-index-buffer-overflow](tenda-fh1202-advsetwrlsafeset-mit-ssid-index-buffer-overflow) | FH1202 | Wrlsafeset / `formWrlsafeset` | `mit_ssid_index` | Buffer Overflow | TBD |
| [tenda-fh1202-webtypelibrary-websiteid-buffer-overflow](tenda-fh1202-webtypelibrary-websiteid-buffer-overflow) | FH1202 | WebTypeLibrary / `formWebTypeLibrary` | `webSiteId` | Buffer Overflow | TBD |
| [tenda-fh1202-safeemailfilter-page-buffer-overflow](tenda-fh1202-safeemailfilter-page-buffer-overflow) | FH1202 | SafeEmailFilter / `fromSafeEmailFilter` | `page` | Buffer Overflow | TBD |
| [tenda-fh1202-natsaticsetting-page-buffer-overflow](tenda-fh1202-natsaticsetting-page-buffer-overflow) | FH1202 | NatSaticSetting / `fromNatStaticSetting` | `page` | Buffer Overflow | TBD |
| [tenda-fh1202-dhcplistclient-page-buffer-overflow](tenda-fh1202-dhcplistclient-page-buffer-overflow) | FH1202 | DhcpListClient / `fromDhcpListClient` | `page` | Buffer Overflow | TBD |
| [tenda-fh1202-p2plistfilter-page-buffer-overflow](tenda-fh1202-p2plistfilter-page-buffer-overflow) | FH1202 | P2pListFilter / `fromP2pListFilter` | `page` | Buffer Overflow | TBD |
| [tenda-i3-setcfm-funcpara1-buffer-overflow](tenda-i3-setcfm-funcpara1-buffer-overflow) | i3 | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow | VDB-349766 · CVE-2026-3799 · EUVD-2026-10293 |
| [tenda-i3-setautoping-ping1-buffer-overflow](tenda-i3-setautoping-ping1-buffer-overflow) | i3 | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow | VDB-349768 · CVE-2026-3801 · EUVD-2026-10292 |
| [tenda-i3-setautoping-ping2-buffer-overflow](tenda-i3-setautoping-ping2-buffer-overflow) | i3 | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow | VDB-349768 · CVE-2026-3801 · EUVD-2026-10292 |
| [tenda-i3-formexeCommand-cmdinput-buffer-overflow](tenda-i3-formexeCommand-cmdinput-buffer-overflow) | i3 | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow | VDB-349769 · CVE-2026-3802 · EUVD-2026-10296 |
| [tenda-i3-formWifiMacFilterGet-index-buffer-overflow](tenda-i3-formWifiMacFilterGet-index-buffer-overflow) | i3 | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow | VDB-349770 · CVE-2026-3803 · EUVD-2026-10297 |
| [tenda-i3-formWifiMacFilterSet-index-buffer-overflow](tenda-i3-formWifiMacFilterSet-index-buffer-overflow) | i3 | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow | VDB-349771 · CVE-2026-3804 |
| [tenda-i3-formWifiMacFilterSet-go-buffer-overflow](tenda-i3-formWifiMacFilterSet-go-buffer-overflow) | i3 | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow | TBD |
| [tenda-i3-formwrlSSIDget-index-buffer-overflow](tenda-i3-formwrlSSIDget-index-buffer-overflow) | i3 | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow | VDB-350405 · CVE-2026-3970 · GCVE-100-350405 |
| [tenda-i3-formwrlSSIDset-index-buffer-overflow](tenda-i3-formwrlSSIDset-index-buffer-overflow) | i3 | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow | VDB-350406 · CVE-2026-3971 · GCVE-100-350406 |
| [tenda-i3-formwrlSSIDset-go-buffer-overflow](tenda-i3-formwrlSSIDset-go-buffer-overflow) | i3 | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow | VDB-350406 · CVE-2026-3971 · GCVE-100-350406 |
| [tenda-w3-setcfm-funcpara1-buffer-overflow](tenda-w3-setcfm-funcpara1-buffer-overflow) | w3 | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow | TBD |
| [tenda-w3-setautoping-ping1-buffer-overflow](tenda-w3-setautoping-ping1-buffer-overflow) | w3 | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow | TBD |
| [tenda-w3-setautoping-ping2-buffer-overflow](tenda-w3-setautoping-ping2-buffer-overflow) | w3 | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow | TBD |
| [tenda-w3-formexeCommand-cmdinput-buffer-overflow](tenda-w3-formexeCommand-cmdinput-buffer-overflow) | w3 | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow | TBD |
| [tenda-w3-formWifiMacFilterGet-index-buffer-overflow](tenda-w3-formWifiMacFilterGet-index-buffer-overflow) | w3 | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow | TBD |
| [tenda-w3-formWifiMacFilterSet-index-buffer-overflow](tenda-w3-formWifiMacFilterSet-index-buffer-overflow) | w3 | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow | TBD |
| [tenda-w3-formWifiMacFilterSet-go-buffer-overflow](tenda-w3-formWifiMacFilterSet-go-buffer-overflow) | w3 | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow | TBD |
| [tenda-w3-formwrlSSIDget-index-buffer-overflow](tenda-w3-formwrlSSIDget-index-buffer-overflow) | w3 | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow | TBD |
| [tenda-w3-formwrlSSIDset-index-buffer-overflow](tenda-w3-formwrlSSIDset-index-buffer-overflow) | w3 | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow | TBD |
| [tenda-w3-formwrlSSIDset-go-buffer-overflow](tenda-w3-formwrlSSIDset-go-buffer-overflow) | w3 | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow | TBD |
