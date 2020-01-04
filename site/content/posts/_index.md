---
title: dnscrypt.uk
date: 2019-11-09T19:21:40.000Z
description: 'Introduction'
---

dnscrypt.uk is a public DNSCrypt service hosted in the UK

## What is dnscrypt
from [dnscrypt.info](https://dnscrypt.info)

> DNSCrypt is a protocol that authenticates communications between a DNS client and a DNS resolver. It prevents DNS spoofing. It uses cryptographic signatures to verify that responses originate from the chosen DNS resolver and haven’t been tampered with.
> It is an open specification, with free and open source reference implementations, and it is not affiliated with any company nor organization.
> Free, DNSCrypt-enabled resolvers are available all over the world.

As well as having secure DNS, what about building a child friendly DNS Server for the house that filters adult content - ideas [here](https://wiki.alpinelinux.org/wiki/DNSCrypt-Proxy)

## How to connect

Clients exist for linux, windows, osx, ios and android.  All can be found here
[dnscrypt.info/implementations](https://dnscrypt.info/implementations)

A really simple solution is to use DNSCrypt-Proxy - [https://github.com/DNSCrypt/dnscrypt-proxy]

## Hosting
dnscrypt.uk hosts two services - dnscrypt.uk (on a DigitalOcean droplet ) and v.dnscrypt.uk (on a vultr high frequency compute).
Both services also host function as anonymous relays.

## Stamp IPV4

The specification for DNS Stamps is [here](https://dnscrypt.info/stamps-specifications/)

{{% block info %}}
sdns://AQcAAAAAAAAAEjEzOS41OS4yMDAuMTE2OjQ0MyBxkKwJmxhDAMvj-aF2TcFOK16cSI5EpMxBJG3Ze0lRvBsyLmRuc2NyeXB0LWNlcnQuZG5zY3J5cHQudWs
sdns://AQcAAAAAAAAAEzEwNC4yMzguMTg2LjE5Mjo0NDMg7Uk9jOrXkGZPBjxHt5WaI2ktfJA2PJ5DzLWRe-W0HuUdMi5kbnNjcnlwdC1jZXJ0LnYuZG5zY3J5cHQudWs
{{% /block %}}

## Stamp IVP6

{{% block info %}}
sdns://AQcAAAAAAAAAHlsyYTAzOmIwYzA6MTplMDo6MmUzOmUwMDFdOjQ0MyBxkKwJmxhDAMvj-aF2TcFOK16cSI5EpMxBJG3Ze0lRvBsyLmRuc2NyeXB0LWNlcnQuZG5zY3J5cHQudWs
sdns://AQcAAAAAAAAALFsyMDAxOjE5ZjA6NzQwMjoxNTc0OjU0MDA6MmZmOmZlNjY6MmNmZl06NDQzIO1JPYzq15BmTwY8R7eVmiNpLXyQNjyeQ8y1kXvltB7lHTIuZG5zY3J5cHQtY2VydC52LmRuc2NyeXB0LnVr
{{% /block %}}

## Server Details
### digitalocean host

| servername    |                     dnscrypt.uk |
|---------------|--------------------------------:|
| providername  |     2.dnscrypt-cert.dnscrypt.uk |
| ipv4 address  |                  139.59.200.116 |
| ipv6 address  |        2a03:b0c0:1:e0::2e3:e001 |
| protocol/port |           UDP and TCP, port 443 |
| relay        |            anon-dnscrypt.uk-ipv4 |
|                |          anon-dnscrypt.uk-ipv6 |

### vultr host

| servername    |v.dnscrypt.uk |
|---------------|---------------------------------------:|
| providername  | 2.dnscrypt-cert.v.dnscrypt.uk |
| ipv4 address  | 104.238.186.192 |
| ipv6 address  | 2001:19f0:7402:1574:5400:2ff:fe66:2cff |
| protocol/port |UDP and TCP, port 443 |
| relay         |anon-v.dnscrypt.uk-ipv4 |
|               |anon-v.dnscrypt.uk-ipv6  |


## STATUS

Status page available here [dnscrypt status](https://status.dnscrypt.uk)

