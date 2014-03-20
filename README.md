pixelserv
=========

A tiny webserver to serve a transparent single pixel graphic or blank text/html replies for ad blocking use.

pixelserv is meant to be run in routers together with a list of blocked adserver domains from dnsmasq or a computer's hosts file.  

This release is built with Openwrt toolchain and have been tested on Atheros-based routers like TP-Link WR1043N running Openwrt and Gargoyle firmwares.

- https://github.com/opav/pixelserv-openwrt/releases

Installation
====

Unzip or copy bin/pixelserv to your router's /bin folder and run it.

May add a guide later but meanwhile please search for the many guides already online on how to use pixelserv with dnsmasq or hosts file.


Version
====

V34.1  minor changes like bigger buffer, added ip/port info in abort msgs etc.


Credits
====

Originally written in C and vastly improved by mstombs since 2009 @ http://www.linksysinfo.org/index.php?threads/pixelserv-compiled-to-run-on-router-wrt54g.30509/page-3#post-235434

Based off demo server.c code from Beej @ http://beej.us/guide/bgnet/ and single pixel gif http string from Piet Wintjens perl script.

