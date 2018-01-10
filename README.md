<<<<<<< HEAD
## ss-verbose
Based on [shadowsocks-libev-3.1.1.tar.gz](https://github.com/shadowsocks/shadowsocks-libev/releases/download/v3.1.1/shadowsocks-libev-3.1.1.tar.gz)
=======
# shadowsocks-libev

## Intro

[Shadowsocks-libev](https://shadowsocks.org) is a lightweight secured SOCKS5
proxy for embedded devices and low-end boxes.

It is a port of [Shadowsocks](https://github.com/shadowsocks/shadowsocks)
created by [@clowwindy](https://github.com/clowwindy), and maintained by
[@madeye](https://github.com/madeye) and [@linusyang](https://github.com/linusyang).

Current version: 3.1.2 | [Changelog](debian/changelog)

Travis CI: [![Travis CI](https://travis-ci.org/shadowsocks/shadowsocks-libev.svg?branch=master)](https://travis-ci.org/shadowsocks/shadowsocks-libev)
>>>>>>> origin/original

## Features
- ss-local
    + local dns cache
    + outbound block list
    + enable syslog by -w
- ss-server
    + log client ip in verbose mode
    + remove ipv6 dns lookup
