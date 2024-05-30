---
authors:
  - "0x4248"
tags:
  - Software
  - Networks
aliases:
  - lightweight directory access protocol
  - LDAP
  - ldap
Ports:
  - "4510"
  - "4511"
---
**Lightweight directory access protocol** (LDAP) is a directory services protocol used for accessing and managing directory information. This service provides a important role in developing a [[Intranet|intranet]].
## Protocol
The client will start by connecting to a LDAP server on port 389 (or 636 for SSL). The client will then send a bind request to the server. The server will then respond with a bind response. The client will then send a search request to the server. The server will then respond with a search response. The client will then send an unbind request to the server. The server will then respond with an unbind response. The client will then close the connection to the server.
### Requests
There are 8 different types of requests that can be sent to the server these are:

- Bind Request
- Search Request
- Unbind Request
- Modify Request
- Add Request
- Delete Request
- Modify DN Request
- Compare Request
- Abandon Request

---
## See also
- [[Real Time Streaming Protocol|RTSP]]
- [[Server Message Block|SMB]]
- [[Network File System|NFS]]
- [[File Transfer Protocol|FTP]]
