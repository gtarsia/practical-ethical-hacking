
# Scanning with nmap

Author first runs `arp-scan -l` to scan his, what I assume is,
his local network.

Then uses `netdiscover`, but it doesn't work for me for some reason.

## Stealth scanning

Author describes what stealth scanning is, even though it's not really stealth,
because good security can detect it (although 80% of the times he does assesments
it's not detected).

TCP uses a 3-way handshake to establish a connection.

A SYN packet sent by us. A SYN packet and an ACK packet sent by remote.
And an ACK packet sent by us.

In "stealth scanning" we send a RST packet instead of the last ACK packet.
Also called TCP SYN.

## nmap

nmap used to enable "sealth scanning" with `-sS` flag,
but now it's done by default.

Then explains the flags he normally uses:

### `-T4`

`-TX` where `X` goes from `1` to `5`. Author says `5` might be too fast because
you might miss something

### `-p-`

This means "scan all ports".

We can leave it off completely which would scan top 1000 ports, such as
80, 443, etc.

But we want to scan all ports because sometimes some obscure services
have the ports opened.

`-p` lets you specify the ports, like `-p 80,443` and so on.

### `-A`

This gives us version information, OS info, fingerprinting, etc.
This flag can be very slow, so maybe it's best to not use it with `-p-`

