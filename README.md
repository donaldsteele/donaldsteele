### Hi, I'm Don

I've been writing software for more than 20 years. These days I build self-hosted tools for
local networks and cross-platform desktop apps, mostly in Go, Rust, C and C#.

Most of what I make has the same shape: one binary for Windows, macOS and Linux, no cloud
account, a local web UI, and an MCP server so an AI agent can drive it.

#### Network and security tools

- **[rocket](https://github.com/donaldsteele/rocket)**: send files and folders between computers
  and phones on your LAN, encrypted, with no cloud and no account. Desktop and Android.
  ([site](https://donaldsteele.github.io/rocket/))
- **[netdiag](https://github.com/donaldsteele/netdiag)**: tells you what is on a network and what
  is wrong with it in about ten seconds, covering live devices, printers (toner, paper, alerts),
  web interfaces, and gateway, DHCP and DNS health.
  ([site](https://donaldsteele.github.io/netdiag/))
- **[bubbles](https://github.com/donaldsteele/bubbles)**: self-hosted chat for a local network,
  with channels, DMs, files, and alerts posted by tools like netdiag. Everything runs over HTTPS
  with its own certificate authority.
  ([site](https://donaldsteele.github.io/bubbles/))
- **[howdah](https://github.com/howdah/howdah)**: an open-source firewall that loads into PHP
  itself and blocks abusive upload and input floods before they exhaust memory, including on
  end-of-life PHP versions that won't get the official fix. Written in Rust and C.
  ([site](https://howdah.org))
- **[overhear](https://github.com/donaldsteele/overhear)**: a passive listener for a local
  network. It never transmits. It decodes what devices announce to everyone (ARP, DHCP, IPv6
  neighbour discovery, mDNS, LLDP and more), keeps a table of the devices it hears, and warns
  about a second DHCP server, an unexpected router or two devices claiming one address. Written
  in Rust. ([site](https://donaldsteele.github.io/overhear/))

#### Desktop apps

- **[pubrs](https://github.com/donaldsteele/pubrs)**: a free, open-source desktop publisher that
  replaces Microsoft Publisher, which reached end of life in October 2026. It opens .pub files and
  exports print-ready PDF/X-4. Written in Rust.
  ([site](https://donaldsteele.github.io/pubrs/))
- **[TrestleBoard](https://github.com/donaldsteele/TrestleBoard)**: a page layout editor for a
  Masonic lodge's monthly newsletter, built with accessibility for older users from the start.
  Uses .NET and Avalonia.
  ([site](https://donaldsteele.github.io/TrestleBoard/))
- **[detangle](https://github.com/donaldsteele/detangle)**: a markdown wiki viewer that resolves
  the links your generator got wrong, and shows which rule it used.
  ([site](https://detangle.dev))
