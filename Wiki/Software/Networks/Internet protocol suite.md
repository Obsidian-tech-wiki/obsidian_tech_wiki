---
authors:
  - "0x4248"
tags:
  - Software
  - Networks
aliases:
  - internet protocol suite
  - Protocol stack
  - protocol stack
---
**Redirected from:** *Protocol stack*
<hr>

The **internet protocol suite** is a set of protocols that the [[Internet|internet]] uses to communicate between other computers and [[Network|networks]].

## Types of internet protocols
The internet protocol suite provides lots of protocols including:
- [[Internet protocol]]
- [[Transmission Control Protocol]]
- [[User Datagram Protocol]]

## Internet protocol suite layers
The internet protocol suite is split into 4 main layers:
- [[#Application layer]]
- [[#Transport layer]]
- [[#Internet layer]]
- [[#Link layer]]

When a device is talking to another device all the layers in the internet protocol stack will be used.
![[Protocol stack flow.png]]
### Application layer
The application layer is a layer that provides services to the user. It is the layer that the user interacts with.

Protocols in the application layer include:
- Domains and naming
    - [[Domain Name System|DNS]] - Domain name system
- Text
    - [[Hypertext Transfer Protocol|HTTP]] - Hypertext transfer protocol
    - [[Secure Hypertext Transfer Protocol|HTTPS]] - Secure hypertext transfer protocol
- Mail
    - [[Simple Mail Transfer Protocol|SMTP]] - Simple mail transfer protocol
    - [[Post Office Protocol|POP3]] - Post office protocol
    - [[Internet Message Access Protocol|IMAP]] - Internet message access protocol
- File transfer
    - [[File Transfer Protocol|FTP]] - File transfer protocol
    - [[Secure File Transfer Protocol|SFTP]] - Secure file transfer protocol
    - [[Trivial File Transfer Protocol|TFTP]] - Trivial file transfer protocol
    - [[Network File System|NFS]] - Network file system
- Remote access
    - [[Telnet]] - Telnet
    - [[Secure Shell|SSH]] - Secure shell
    - [[Remote Desktop Protocol|RDP]] - Remote desktop protocol
    - [[Virtual Network Computing|VNC]] - Virtual network computing
    - [[Remote Frame Buffer|RFB]] - Remote frame buffer
- Network management
    - [[Simple Network Management Protocol|SNMP]] - Simple network management protocol
    - [[Internet Control Message Protocol|ICMP]] - Internet control message protocol
    - [[Internet Group Management Protocol|IGMP]] - Internet group management protocol
- Other
    - [[Dynamic Host Configuration Protocol|DHCP]] - Dynamic host configuration protocol
    - [[Lightweight Directory Access Protocol|LDAP]] - Lightweight directory access protocol
    - [[Network Time Protocol|NTP]] - Network time protocol
    - [[Simple Network Time Protocol|SNTP]] - Simple network time protocol
    - [[Session Initiation Protocol|SIP]] - Session initiation protocol
    - [[Real Time Streaming Protocol|RTSP]] - Real time streaming protocol
    - [[Extensible Messaging and Presence Protocol|XMPP]] - Extensible messaging and presence protocol
    - [[Internet Relay Chat|IRC]] - Internet relay chat

### Transport layer
The transport layer is a layer that provides services to the application layer. It is the layer that the application layer interacts with.

Protocols in the transport layer include:
- [[Transmission Control Protocol|TCP]] - Transmission control protocol
- [[User Datagram Protocol|UDP]] - User datagram protocol
- [[Datagram Congestion Control Protocol|DCCP]] - Datagram congestion control protocol
- [[Stream Control Transmission Protocol|SCTP]] - Stream control transmission protocol
- [[Resource Reservation Protocol|RSVP]] - Resource reservation protocol

### Internet layer
The internet layer is a layer that provides services to the transport layer. It interacts with the transport layer and the link layer.

Protocols in the internet layer include:
- [[Internet Protocol|IP]] - Internet protocol
- [[Internet Control Message Protocol|ICMP]] - Internet control message protocol
- [[Internet Group Management Protocol|IGMP]] - Internet group management protocol
- [[Internet Protocol version 6|IPv6]] - Internet protocol version 6
- [[Internet Protocol version 4|IPv4]] - Internet protocol version 4
- [[Internet Protocol Security|IPsec]] - Internet protocol security

### Link layer
The link layer is a layer that provides services to the internet layer. It interacts with the internet layer and the physical layer.