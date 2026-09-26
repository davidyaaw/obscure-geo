# obscure-geo

Trimmed `geosite.dat` / `geoip.dat` for Xray clients (Happ, Incy), cut from
[runetfreedom/russia-v2ray-rules-dat](https://github.com/runetfreedom/russia-v2ray-rules-dat).
Category contents are copied unchanged; only unused categories are dropped.

- geosite: `category-ru`, `ru-blocked`, `category-ads-all`, `win-spy`, `steam`, `epicgames`, `riot`, `youtube`, `telegram`
- geoip: `ru`, `private`

Each tag equals the upstream release it was built from. Use a pinned URL:

    https://cdn.jsdelivr.net/gh/davidyaaw/obscure-geo@<tag>/release/geosite.dat
    https://cdn.jsdelivr.net/gh/davidyaaw/obscure-geo@<tag>/release/geoip.dat
