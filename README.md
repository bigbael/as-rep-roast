# as-rep-roast

# Author
Jason Martinsen

Python code to execute an AS-REP Roasting attack.

USE ONLY AGAINST AUTHORIZED TARGETS

### Usage :
```
USAGE:
as-rep-roast.py -u <userName>@<domainName> -d <domainControlerAddr>

Hashcat compatible output will be piped to screen and to hashcat.out file.
```

This code is based on the code from the below project...

Python Kerberos Exploitation Kit
===

PyKEK (Python Kerberos Exploitation Kit), a python library to manipulate KRB5-related data. (Still in development)

For now, only a few functionalities have been implemented (in a quite Quick'n'Dirty way) to exploit  MS14-068 (CVE-2014-6324) .

More is coming...

# Author
Sylvain Monné

Contact : sylvain dot monne at solucom dot fr

http://twitter.com/bidord

Special thanks to: Benjamin DELPY `gentilkiwi`

# Library content
* kek.krb5: Kerberos V5 ([RFC 4120](https://tools.ietf.org/html/rfc4120)) ASN.1 structures and basic protocol functions
* kek.ccache: Credential Cache Binary Format ([cchache](http://www.gnu.org/software/shishi/manual/html_node/The-Credential-Cache-Binary-File-Format.html))
* kek.pac: Microsoft Privilege Attribute Certificate Data Structure ([MS-PAC](http://msdn.microsoft.com/en-us/library/cc237917.aspx))
* kek.crypto: Kerberos and MS specific cryptographic functions
