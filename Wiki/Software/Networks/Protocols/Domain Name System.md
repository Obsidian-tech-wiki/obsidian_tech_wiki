---
authors: 
  - "0x4248"
tags:
  - Software
  - Networks
aliases:
  - DNS
  - domain name system
---
The **Domain Name System** (DNS) is a crucial component of the [[Internet|internet]] that plays a fundamental role in translating human-friendly domain names into [[IP address|IP addresses]], which computers use to identify each other on the network. It is like the internet's phone book, allowing users to access [[website|websites]], send emails, and perform various online activities with ease.

## Key concept
A [[DNS server]] will listen for DNS requests and respond with the IP address of the domain. For example if I make the request `example.com` to the DNS server it should respond with the IP address of the domain this could be `10.76.32.3`. The DNS server can also respond with [[IPv6]] addresses for example `f4c1:1850:2416:e52c:ac0f:943e:6ff0:a5b2`.

When you make a DNS request your [[Wiki/Software/Operating systems/Operating system|operating system]] may also [[Cache|cache]] the result locally making it quicker to connect a domain. You can also set a local override on the hosts file on your computer.