
# Scanning with masscan

He runs `masscan -p1-65535 --rate 1000 <ip>` and compares it to `nmap -T4- -p- 192.168.143.128`

For some reason, masscan does not return results for me.

Author explains that some tools are faster than others sometimes.
