# public-resolvers

This is a list of public DNS resolvers supporting the
DNSCrypt and DNS-over-HTTP2 protocols.

This list is maintained by Thejus Paul

Adjust the `require_*` options in dnscrypt-proxy to filter that list
according to your needs.

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'public-resolvers']
    urls = ['https://raw.githubusercontent.com/Thejus-Paul/my_dnscrypt_resolvers/master/public-resolvers.md']
    minisign_key = 'RWRZQ0WkSMYcLgSGL6YHPDrvUbgsqHcGnP63oAvJP8wlwBMU2vVg2YKW'
    cache_file = 'public-resolvers.md'

--


## dns.digitale-gesellschaft.ch

Public DoH resolver operated by the Digital Society (https://www.digitale-gesellschaft.ch).
Hosted in Zurich, Switzerland.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAADTE4NS45NS4yMTguNDKgMob_ZaZfrzIIXuoTiMNzi6fjeHPJBszjxKKLTMKliYigRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984gzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYcZG5zLmRpZ2l0YWxlLWdlc2VsbHNjaGFmdC5jaAovZG5zLXF1ZXJ5

## faelix-ch-ipv4

An open DoH resolver operated by https://faelix.net/ with nodes in UK and CH.

sdns://AQcAAAAAAAAAEzE4NS4xMzQuMTk2LjU0Ojg0NDMgfsvvPi8BgDKNYODh0ewj5Oh32OoJoZNwGgTWs8C-i-EfMi5kbnNjcnlwdC1jZXJ0LnJkbnMuZmFlbGl4Lm5ldA

## doh-ch-blahdns

Blocks ad and Tracking, no Logging, DNSSEC, Hosted in Switzerland. By https://blahdns.com/

sdns://AgMAAAAAAAAADDQ1LjkxLjkyLjEyMQASZG9oLWNoLmJsYWhkbnMuY29tCi9kbnMtcXVlcnk

## pf-dnscrypt

by post-factum | Zürich, Switzerland | Non-logging | Non-filtering | DNSSEC | https://dns.post-factum.tk

sdns://AQcAAAAAAAAAFDE0MC4yMzguMjE1LjE5Mjo4NDQzIH2l4fL6H6BQcKWfdf9ZnrvWxZL_vxKUtQMcWDdZwB6bHjIuZG5zY3J5cHQtY2VydC5wb3N0LWZhY3R1bS50aw
