
# Common ports and protocols

TCP
* FTP (21)
* SSH (22)
* Telnet (23)
* SMTP (25)
* DNS (53)
* HTTP (80) / HTTPS (443)
* POP3 (110)
* SMB (139 + 445)
* IMAP (143)

UDP
* DNS(53)

## Details about them

Telnet is the same as ssh, except Telnet is in plaintext and SSH is encrypted

SMB is  used to be just port 139,
but in later versions of windwos 445 is used also.

SMB has had some insane exploits,
for example the wannacry virus.

DNS uses both TCP and UDP protocols.

DHCP associates you with an IP address
based on your MAC address.

If we encounter SNMP, we can gather some information from it.
