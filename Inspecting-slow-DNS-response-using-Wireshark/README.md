# Inspecting slow DNS response using Wireshark

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


Useful links:
--
[Troubleshooting DNS servers](https://docs.microsoft.com/en-us/windows-server/networking/dns/troubleshoot/troubleshoot-dns-server)
