
# Other nmap flags

He checks the `nmap --help` and explains the following options:

### `-sn`

Can scan an entire network just for pings.

### `-Pn`

Treats all hosts as if they were online, if they don't respond to ping requests.

### `-sU`

You can also scan all the other 65k ports for UDP

It does not have immediate response time, so use it `-p` instead of `-p-`
so it does not take forever.
