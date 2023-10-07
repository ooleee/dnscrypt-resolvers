# public-resolvers

This is an extensive list of public DNS resolvers supporting the
DNSCrypt and DNS-over-HTTP2 protocols.

This list is maintained by Frank Denis <j @ dnscrypt [.] info>

Warning: it includes servers that may censor content, servers that don't
verify DNSSEC records, and servers that will collect and monetize your
queries.

Adjust the `require_*` options in dnscrypt-proxy to filter that list
according to your needs.

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'public-resolvers']
    urls = ['https://raw.githubusercontent.com/ooleee/dnscrypt-resolvers/master/lee/custom-resolvers.md']
    minisign_key = 'RWTo3vUSIJTV9PcPOKJpNLxWbu/Lhv8x+HH49ChEWESaXYMZ2CO0JVW8'
    cache_file = 'custom-resolvers.md'

--

## adguard-dns-doq-ipad-mini

sdns://BAcAAAAAAAAADDk0LjE0MC4xNC40OQAfZmNmZmFmMTMuZC5hZGd1YXJkLWRucy5jb206ODg1Mw

## adguard-dns-doq-ipad-mini-ipv6
sdns://BAcAAAAAAAAAE1syYTEwOjUwYzA6OmRlZDpmZl0AH2ZjZmZhZjEzLmQuYWRndWFyZC1kbnMuY29tOjg4NTM
