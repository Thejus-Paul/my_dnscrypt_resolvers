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

Hosted in Zürich, Switzerland🇨🇭. 

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAADTE4NS45NS4yMTguNDKgMob_ZaZfrzIIXuoTiMNzi6fjeHPJBszjxKKLTMKliYigRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984gzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYcZG5zLmRpZ2l0YWxlLWdlc2VsbHNjaGFmdC5jaAovZG5zLXF1ZXJ5

## dns.digitale-gesellschaft.ch-2

Public DoH resolver operated by the Digital Society (https://www.digitale-gesellschaft.ch).

Hosted in Zürich, Switzerland🇨🇭.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAADTE4NS45NS4yMTguNDOgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984cZG5zLmRpZ2l0YWxlLWdlc2VsbHNjaGFmdC5jaAovZG5zLXF1ZXJ5

## doh-ch-blahdns

Public DoH resolver operated by BlahDNS (https://blahdns.com).

Hosted in Switzerland🇨🇭.

Non-logging, Blocks ad and Tracking, supports DNSSEC. 

sdns://AgMAAAAAAAAADDQ1LjkxLjkyLjEyMQASZG9oLWNoLmJsYWhkbnMuY29tCi9kbnMtcXVlcnk

## pf-dnscrypt

Public DNSCrypt resolver operated by post-factum (https://dns.post-factum.tk).

Hosted in Zürich, Switzerland🇨🇭. 

Non-logging, non-filtering, supports DNSSEC.

sdns://AQcAAAAAAAAAFDE0MC4yMzguMjE1LjE5Mjo4NDQzIH2l4fL6H6BQcKWfdf9ZnrvWxZL_vxKUtQMcWDdZwB6bHjIuZG5zY3J5cHQtY2VydC5wb3N0LWZhY3R1bS50aw

## quad9-dnscrypt-ipv4-primary

Public DNSCrypt resolver from Quad9 (https://quad9.net).

Non-logging, filtering, supports DNSSEC.

sdns://AQMAAAAAAAAADDkuOS45Ljk6ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0

## quad9-dnscrypt-ipv4-alt

Public DNSCrypt resolver from Quad9 (https://quad9.net).

Non-logging, filtering, supports DNSSEC.

stamp = 'sdns://AQMAAAAAAAAAEjE0OS4xMTIuMTEyLjk6ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0'

## quad9-dnscrypt-ipv4-alt2

Public DNSCrypt resolver from Quad9 (https://quad9.net).

Non-logging, filtering, supports DNSSEC.

stamp = 'sdns://AQMAAAAAAAAAFDE0OS4xMTIuMTEyLjExMjo4NDQzIGfIR7jIdYzRICRVQ751Z0bfNN8dhMALjEcDaN-CHYY-GTIuZG5zY3J5cHQtY2VydC5xdWFkOS5uZXQ'

