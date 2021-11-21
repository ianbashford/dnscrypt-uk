

## What is dnscrypt?

Secure, encrypted DNS that prevents DNS spoofing.

DNScrypt.uk is a public DNSCrypt service.

## Where is dnscrypt.uk hosted?

DNSCrypt and DoH services are hosted in the UK on

vultr and digitalocean VMs, and are available on IPV4 and IPV6.

## How to connect?

The easiest client to configure is [DNSCrypt-Proxy](https://github.com/DNSCrypt/dnscrypt-proxy)

IPV4 services can be configured using the 

following entries in dnscrypt-proxy.toml:

```golang
server_names = ['v.dnscrypt.uk-ipv4','dnscrypt.uk-ipv4',

		'v.dnscrypt.uk-doh-ipv4','dnscrypt.uk-doh-ipv4']
```
