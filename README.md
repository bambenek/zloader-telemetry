# zloader-telemetry
Telemetry from the ZLoader malware that is using DNS for C2 communications

Based on the research from ZScalar (https://www.zscaler.com/blogs/security-research/inside-zloader-s-latest-trick-dns-tunneling) research on how the malware was updated to include C2 tunneling via DNS, I took a look what I could find and found 48,000 events (mostly pings) of victims from around the world. Of interest are the 608 IPv6 DNS queries that returned various IPv6 addresses (unlike IPv4 which all returned an IP of 8.8.8.8).

All the DNS telemetry is stored in zloader.csv.

The IPv6 events are stored in zloader-ipv6.csv.
