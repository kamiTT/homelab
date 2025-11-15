# DNS Settings

### Upstream DNS servers

#### \# Quad9
    tls://9.9.9.9
    tls://149.112.112.112
    https://dns.quad9.net/dns-query
    tls://dns.quad9.net

#### \# Cloudfare
    tls://1.1.1.1
    tls://1.0.0.1
    https://dns.cloudflare.com/dns-query
    https://cloudflare-dns.com/dns-query
    tls://1dot1dot1dot1.cloudflare-dns.com

#### \# Mullvad
    https://dns.mullvad.net/dns-query

### Fallback DNS servers
    1.1.1.1
    1.0.0.1
    9.9.9.9
    149.112.112.112

### Bootstrap DNS servers
    9.9.9.10
    149.112.112.10
    149.112.112.112
    194.242.2.2
    1.1.1.1
    1.0.0.1

### Blocklists

| Name | Raw (txt) | Learn More |
| :--- | :--: | :----: | 
| 1Hosts (Pro) | | [link](https://github.com/badmojr/1Hosts) |
| AdGuard DNS filter | [raw](https://adguardteam.github.io/HostlistsRegistry/assets/filter_1.txt) | |
| Dandelion Sprout's Game Console Adblock List | [raw](https://github.com/DandelionSprout/adfilt/blob/master/GameConsoleAdblockList.txt) | [link](https://github.com/DandelionSprout/adfilt) |
| FMHYFilterlist | [raw](https://raw.githubusercontent.com/fmhy/FMHYFilterlist/main/filterlist-basic-abp.txt) | [link](https://github.com/fmhy/FMHYFilterlist) |
| HaGeZi's Badware Hoster Blocklist | | [link](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#hoster) |
| HaGeZi's DynDNS Blocklist | | [link](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#dyndns) |
| HaGeZi's Gambling Blocklist | | [link](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#gambling) |
| HaGeZi's Threat Intelligence Feeds | | [link](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#tif) |
| HaGeZi's Ultimate Blocklist | | [link](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#ultimate) |
| HaGeZi's Windows/Office Tracker Blocklist | | []() |
| NoCoin Filter List | [raw](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/nocoin.txt&title=NoCoin%20Filter%20List) | [link](https://github.com/hoshsadiq/adblock-nocoin-list) |
| Peter Lowe's Blocklist | | |
| Phishing Army | | |
| uBlock₀ filters – Badware risks | | |

### Custom Rules
    ||tadata.crushblocks.com^$important
    ||mesu.g.aaplimg.com^$important
    ||gspe79-cdn.g.aaplimg.com^$important
