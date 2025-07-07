# Watcher-II-2.0 - README
Watcher-II is the 'nftables' rendition of Watcher.
It is currently under development and has the state 'devel'

Revision 2.0 is derived from the production release of Watcher-1.4 and so has all the functionalities of the Watcher-V1 series already implemented.
All iptables/ipset firewall management calls for a legacy 'xtables' firewall are replaced by 'nftables' related calls and collected in ../api/bash/nft.bashlib. So there is rarely a need to deal with native 'nft' commands in Watcher components (modules, dyloaders, Watcher tools)

Watcher-II will support 'firewalld' and a custom nftables firewall.
This repository is currently provided for reference, and people who would like to explore the development.

# Official Resources
None yet

# Milestone
Watcher-II 2.0/Prod
