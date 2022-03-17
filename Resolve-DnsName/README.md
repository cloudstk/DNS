
Resolve DnsName
==
The Resolve-DnsName cmdlet performs a DNS query for the specified name. This cmdlet is functionally similar to the nslookup tool which allows users to query for names.


EXAMPLE 1
--
PowerShell
```
PS C:\> Resolve-DnsName -Name www.bing.com
```
This example resolves a name using the default options.

EXAMPLE 2
--
PowerShell

```
PS C:\> Resolve-DnsName -Name www.bing.com -Server 10.0.0.1
```

This example resolves a name against the DNS server at 10.0.0.1.

EXAMPLE 3
--
PowerShell

```
PS C:\> Resolve-DnsName -Name www.bing.com -Type A
```

This example queries for A type records for name www.bing.com.

EXAMPLE 4
--
PowerShell
```
PS C:\> Resolve-DnsName -Name www.bing.com -DnsOnly
```

This example resolves a name using only DNS. LLMNR and NetBIOS queries are not issued.
