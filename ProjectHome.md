# General #
DroidSheep is a simple Android tool for web session hijacking (sidejacking).
It listens for HTTP packets sent via a wireless (802.11) network connection and extracts the session id from these packets in order to reuse them.

DroidSheep can capture sessions using the libpcap library and supports:
**OPEN Networks**WEP encrypted networks
**WPA and WPA2 encrypted networks (PSK only)**

DroidSheep is not intended to steal identities or endamage anybody, but to show the weak security of non-ssl webservices.

This software uses libpcap and arpspoof.

THIS SOFTWARE IS NOT INTENDED TO STEAL IDENTITIES, BUT ONLY FOR SECURITY ANALYSIS!