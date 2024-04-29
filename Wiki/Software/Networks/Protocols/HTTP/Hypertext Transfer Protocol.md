---
authors:
  - "0x4248"
tags:
  - Software
  - Networks
aliases:
  - hyper text transfer protocol
  - HTTP
Key date: 1991-01-01
---
The **Hyper text transfer protocol** (HTTP) is a application layer protocol of the [[Internet protocol suite|internet protocol suite]]. HTTP is one of the main protocols that is used on the [[World wide web|world wide web]].  
## HTTP Versions
HTTP has gone through several versions over the years. 

| Version  | Year introduced | Current stautus |
| -------- | --------------- | --------------- |
| HTTP/0.9 | 1991            | Depreciated     |
| HTTP/1.0 | 1996            | Depreciated     |
| HTTP/1.1 | 1997            | Standard        |
| HTTP/2   | 2015            | Standard        |
| HTTP/3   | 2022            | Standard        |

## HTTP request messages
A request message is sent to the target [[server]] from the [[client]].
### Request syntax
A [[client]] sends a request message to the [[server]] which contain:
- The request line which has a request method that is case sensitive, a apace, the path, a space and then the HTTP version
```
GET /index.html HTTP/1.1
```
- The request headers fields
```
Host: www.example.com
Accept: text/html,application/xhtml+xml,application/xml
```
- An empty line
- An optional message body

> [!note]
> Header fields are optional except for `Host: hostname`

## Request methods
*Main wiki page: [[HTTP Request methods]]*
A HTTP request defines what action is to be performed.

- [[GET]]
- [[POST]]
- [[PUT]]
- [[DELETE]]
- [[PATCH]]
- [[HEAD]]
- [[OPTIONS]]
- [[CONNECT]]
- [[TRACE]]

## Response messages
A response message is sent from the [[server]] to the [[client]].

### Response syntax
A server sends a response message which consists of:
- A status line which contains the protocol and response code
```http
HTTP/1.0 200 OK
```

### Response status codes
*Main wiki page: [[HTTP Response status codes]]*

HTTP sends a status code with every response. The status code is a 3 digit number that indicates the status of the request.

- **1xx** Informational responses
- **2xx** Success
- **3xx** Redirection
- **4xx** Client errors
- **5xx** Server errors

---
## See also
- [[Secure Hypertext Transfer Protocol|HTTPS]]
- [[Web server]]