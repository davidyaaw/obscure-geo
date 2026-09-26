# obscure-geo

Trimmed `geosite.dat` / `geoip.dat` for Xray clients (Happ, Incy), cut from
[runetfreedom/russia-v2ray-rules-dat](https://github.com/runetfreedom/russia-v2ray-rules-dat).
Category contents are copied unchanged; only unused categories are dropped.

- geosite: `category-ru`, `obscure-ru-blocked`, `win-spy`, `steam`, `epicgames`, `riot`, `youtube`, `telegram`
  (`obscure-ru-blocked` is the part of upstream `ru-blocked` under `.ru`/`.su`/`.xn--p1ai`,
  `category-ru` and a few direct names; tags up to `202609251926` carry the full
  `ru-blocked` and `category-ads-all` instead)
- geoip: `ru`, `private`

Tags are `<upstream release>` or `<upstream release>-<build>`. Use a pinned URL:

    https://cdn.jsdelivr.net/gh/davidyaaw/obscure-geo@<tag>/release/geosite.dat
    https://cdn.jsdelivr.net/gh/davidyaaw/obscure-geo@<tag>/release/geoip.dat
