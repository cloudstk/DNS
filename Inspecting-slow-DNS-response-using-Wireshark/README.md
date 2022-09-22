Inspecting slow DNS response using Wireshark
---
DNS Record Types
--
| Record        | Description |
| ------------- | ------------- |
| A             | IPv4 address  |
| AAAA          | IPv6 address  |
| CNAME         | Canonical name record  |
| MX            | Mail record  |
| NS            | Nameserver record  |
| PTR           | Pointer record  |
| SOA           | Start of authority record  |
| SRV           | Service location record  |
| TXT           | Text record  |

DNS Header Flags
--
| Flag          | Description |
| ------------- | ------------- |
| AA            | Authoritative Answer  |
| TC            | Truncated Response  |
| RD            | Recursion Desired  |
| RA            | Recursion Available  |
| Z             | Reserved for future use. set this field to 0 |

RCODE Response code - this 4 bit field is set as part of responses. The values have the following
interpretation:

0 - No error condition

1 - Format error - The name server was unable to interpret the query.

2 - Server failure - The name server was unable to process this query due to a problem with
the name server.

3 - Name Error - Meaningful only for responses from an authoritative name server, this code
signifies that the domain name referenced in the query does not exist.

4 - Not Implemented - The name server does not support the requested kind of query.

5 - Refused - The name server refuses to perform the specified operation for policy reasons.

Useful links:
---

[Troubleshooting DNS servers](https://docs.microsoft.com/en-us/windows-server/networking/dns/troubleshoot/troubleshoot-dns-server)

[How the Domain Name System (DNS) Works](https://www.verisign.com/en_US/website-presence/online/how-dns-works/index.xhtml)
