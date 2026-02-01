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
