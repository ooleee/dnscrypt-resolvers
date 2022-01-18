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

## adguard-dns-doh

Remove ads and protect your computer from malware (over DoH)

sdns://AgMAAAAAAAAADzE3Ni4xMDMuMTMwLjEzMCCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGQ9kbnMuYWRndWFyZC5jb20KL2Rucy1xdWVyeQ


## alidns-doh

A public DNS resolver that supports DoH/DoT in mainland China, provided by Alibaba-Cloud.

Warning: GFW filtering rules are applied by that resolver.

Homepage: https://alidns.com/

sdns://AgAAAAAAAAAACTIyMy41LjUuNSAUZf-XFWhwvjDwNPWQzx8E3VDwpSDoT4pSfpwaLofrgA5kbnMuYWxpZG5zLmNvbQovZG5zLXF1ZXJ5
