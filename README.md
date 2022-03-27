# Tor-Relays-Lists
Tor Relays Lists

```
https://tor-relays.0xc0d3.xyz/exits.txt
https://tor-relays.0xc0d3.xyz/exits-ipv4.txt
https://tor-relays.0xc0d3.xyz/exits-ipv6.txt
https://tor-relays.0xc0d3.xyz/relays.txt
https://tor-relays.0xc0d3.xyz/relays-ipv4.txt
https://tor-relays.0xc0d3.xyz/relays-ipv6.txt
https://tor-relays.0xc0d3.xyz/updated.txt
```

The Onionoo API offers authoritative information on the state of the Tor Network, including the IP addresses of all relays and the purposes they serve (i.e., guard, exit, etc.). However, JSON-based REST APIs and the Tor Project's exit list aren't the friendliest methods for maintaining firewall rules and other applications that are supposed to consume IP lists.

If you would like a raw list of Tor relays you can visit these links below, where you will find a selection of maintained IP address lists for relays that participate in the Tor Network.

```
    exits.txt: Exit relays only, IPv4 and IPv6. Use this list to block traffic to your site from the Tor Network.
    exits-ipv4.txt: Exit relays only, IPv4 only.
    exits-ipv6.txt: Exit relays only, IPv6 only.
    relays.txt: All relays within the Tor Network, exit and non-exit, IPv4 and IPv6.
    relays-ipv4.txt: All relays, IPv4 only.
    relays-ipv6.txt: All relays, IPv6 only.
    updated.txt: The time in UTC when the list was last updated.
```

You could use the Tor Project's bulk exit list, but we found it to be inaccurate, missing IP addresses that are exit relays and including some that aren't.
