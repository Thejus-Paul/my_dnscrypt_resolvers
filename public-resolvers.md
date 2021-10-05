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

sdns://AgcAAAAAAAAAAKA-GhoPbFPz6XpJLVcIS1uYBwWe4FerFQWHb9g_2j24OKBoo-sB-l8CxNNfOhHQBMrwiyJL7qfXnFiMfxPIYTNgLqDvR4Wu5wydV1_nM4MG2T6nlhHl_tzvU2LdZsmLYLstvSAcVDa2UaK1QVwWz9ltGpcJ_ZyPJ-73XPlz2YL_5o5Y8BxkbnMuZGlnaXRhbGUtZ2VzZWxsc2NoYWZ0LmNoCi9kbnMtcXVlcnk

## faelix

An open DoH resolver operated by https://faelix.net/ with nodes in UK and CH.

sdns://AgcAAAAAAAAADDE5NS4zMC45NC4yOCA-GhoPbFPz6XpJLVcIS1uYBwWe4FerFQWHb9g_2j24OA1kb2guZmZtdWMubmV0Ci9kbnMtcXVlcnk
