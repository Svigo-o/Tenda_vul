# Tenda_vul
Tenda 路由器漏洞复现与分析记录。

## 漏洞列表

| 目录 | 产品 | 接口/功能 | 参数 | 类型 |
| --- | --- | --- | --- | --- |
| [tenda-fh1202-advsetwrlsafeset-mit-ssid-buffer-overflow](tenda-fh1202-advsetwrlsafeset-mit-ssid-buffer-overflow) | FH1202 | Wrlsafeset / `formWrlsafeset` | `mit_ssid` | Buffer Overflow |
| [tenda-fh1202-advsetwrlsafeset-mit-ssid-index-buffer-overflow](tenda-fh1202-advsetwrlsafeset-mit-ssid-index-buffer-overflow) | FH1202 | Wrlsafeset / `formWrlsafeset` | `mit_ssid_index` | Buffer Overflow |
| [tenda-fh1202-webtypelibrary-websiteid-buffer-overflow](tenda-fh1202-webtypelibrary-websiteid-buffer-overflow) | FH1202 | WebTypeLibrary / `formWebTypeLibrary` | `webSiteId` | Buffer Overflow |
| [tenda-fh1202-safeemailfilter-page-buffer-overflow](tenda-fh1202-safeemailfilter-page-buffer-overflow) | FH1202 | SafeEmailFilter / `fromSafeEmailFilter` | `page` | Buffer Overflow |
| [tenda-fh1202-natsaticsetting-page-buffer-overflow](tenda-fh1202-natsaticsetting-page-buffer-overflow) | FH1202 | NatSaticSetting / `fromNatStaticSetting` | `page` | Buffer Overflow |
| [tenda-fh1202-dhcplistclient-page-buffer-overflow](tenda-fh1202-dhcplistclient-page-buffer-overflow) | FH1202 | DhcpListClient / `fromDhcpListClient` | `page` | Buffer Overflow |
| [tenda-fh1202-p2plistfilter-page-buffer-overflow](tenda-fh1202-p2plistfilter-page-buffer-overflow) | FH1202 | P2pListFilter / `fromP2pListFilter` | `page` | Buffer Overflow |
| [tenda-i3-setcfm-funcpara1-buffer-overflow](tenda-i3-setcfm-funcpara1-buffer-overflow) | i3 | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow |
| [tenda-i3-setautoping-ping1-buffer-overflow](tenda-i3-setautoping-ping1-buffer-overflow) | i3 | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow |
| [tenda-i3-setautoping-ping2-buffer-overflow](tenda-i3-setautoping-ping2-buffer-overflow) | i3 | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow |
| [tenda-i3-formexeCommand-cmdinput-buffer-overflow](tenda-i3-formexeCommand-cmdinput-buffer-overflow) | i3 | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow |
| [tenda-i3-formWifiMacFilterGet-index-buffer-overflow](tenda-i3-formWifiMacFilterGet-index-buffer-overflow) | i3 | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow |
| [tenda-i3-formWifiMacFilterSet-index-buffer-overflow](tenda-i3-formWifiMacFilterSet-index-buffer-overflow) | i3 | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow |
| [tenda-i3-formWifiMacFilterSet-go-buffer-overflow](tenda-i3-formWifiMacFilterSet-go-buffer-overflow) | i3 | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow |
| [tenda-i3-formwrlSSIDget-index-buffer-overflow](tenda-i3-formwrlSSIDget-index-buffer-overflow) | i3 | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow |
| [tenda-i3-formwrlSSIDset-index-buffer-overflow](tenda-i3-formwrlSSIDset-index-buffer-overflow) | i3 | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow |
| [tenda-i3-formwrlSSIDset-go-buffer-overflow](tenda-i3-formwrlSSIDset-go-buffer-overflow) | i3 | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow |
| [tenda-w3-setcfm-funcpara1-buffer-overflow](tenda-w3-setcfm-funcpara1-buffer-overflow) | w3 | CFM / `formSetCfm` | `funcpara1` | Buffer Overflow |
| [tenda-w3-setautoping-ping1-buffer-overflow](tenda-w3-setautoping-ping1-buffer-overflow) | w3 | AutoPing / `formSetAutoPing` | `ping1` | Buffer Overflow |
| [tenda-w3-setautoping-ping2-buffer-overflow](tenda-w3-setautoping-ping2-buffer-overflow) | w3 | AutoPing / `formSetAutoPing` | `ping2` | Buffer Overflow |
| [tenda-w3-formexeCommand-cmdinput-buffer-overflow](tenda-w3-formexeCommand-cmdinput-buffer-overflow) | w3 | exeCommand / `formexeCommand` | `cmdinput` | Buffer Overflow |
| [tenda-w3-formWifiMacFilterGet-index-buffer-overflow](tenda-w3-formWifiMacFilterGet-index-buffer-overflow) | w3 | WifiMacFilterGet / `formWifiMacFilterGet` | `index` | Buffer Overflow |
| [tenda-w3-formWifiMacFilterSet-index-buffer-overflow](tenda-w3-formWifiMacFilterSet-index-buffer-overflow) | w3 | WifiMacFilterSet / `formWifiMacFilterSet` | `index` | Buffer Overflow |
| [tenda-w3-formWifiMacFilterSet-go-buffer-overflow](tenda-w3-formWifiMacFilterSet-go-buffer-overflow) | w3 | WifiMacFilterSet / `formWifiMacFilterSet` | `GO` | Buffer Overflow |
| [tenda-w3-formwrlSSIDget-index-buffer-overflow](tenda-w3-formwrlSSIDget-index-buffer-overflow) | w3 | wifiSSIDget / `formwrlSSIDget` | `index` | Buffer Overflow |
| [tenda-w3-formwrlSSIDset-index-buffer-overflow](tenda-w3-formwrlSSIDset-index-buffer-overflow) | w3 | wifiSSIDset / `formwrlSSIDset` | `index` | Buffer Overflow |
| [tenda-w3-formwrlSSIDset-go-buffer-overflow](tenda-w3-formwrlSSIDset-go-buffer-overflow) | w3 | wifiSSIDset / `formwrlSSIDset` | `GO` | Buffer Overflow |
