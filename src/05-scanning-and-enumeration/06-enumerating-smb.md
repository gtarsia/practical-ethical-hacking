
# Enumerating smb

The user notices that port 139 is open thanks to `nmap`.

After this, the user runs `msfconsole` (metasploit).

On this console, author runs `search smb` to search any vulnerabilities
related to smb.

From the result of this, author explains you can run `use <name>` or `use <search_result_number>`.

The author specifically runs `use auxiliary/scanner/smb/smb_version` to obtain the version of kioptrix smb.

After running the `use` command, you can get info about it
by running `info`.

Here it defines the "arguments" this module requires to use.

You set these by doing `set <name> <value>`.

In our case we run `set RHOSTS <kioptrix_ip>`, and then we run,
from which we obtain `Host could not be identified: Unix (Samba 2.2.1a)`,
which author notes down.

Author then runs `smbclient -L \\\\<kioptrix_ip>`.
(I had to have `client max protocol = CORE` in /etc/samba/smb.conf)
This then lists out a couple of services.
