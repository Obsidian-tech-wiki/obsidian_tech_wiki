---
authors:
  - "0x4248"
tags:
  - Software
  - Networks
aliases:
  - secure shell
  - ssh
  - SSH
Ports:
  - "22"
---
SSH is a secure alternative to Telnet for remote system access. It [[Encryption|encrypts]] the communication, enhancing [[Cybersecurity|security]]. When a user logs into a SSH session they are commonly greeted with a shell from the server that the client is connected to.

## Usage
To open an SSH session on most computers you use the `ssh` command.
```bash
ssh user@host
```

If the SSH uses password authentication then it will ask for the password.
## Authentication
The secure shell protocol uses two authentication methods [[Public and private keys|public and private keys]] and password authentication.

## Protocol
The SSH protocol runs on port `22` and is encrypted between the server and the client.
___
## See also
- [[Telnet]]
- [[Remote Desktop Protocol|Remote Desktop Protocol (RDP)]]