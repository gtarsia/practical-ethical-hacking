
# Hunting subdomains

The author uses `sublist3r` to get subdomains of a site, similar to theharvester but it returns more data.

He runs `sublist3er -d tesla.com`.

He then browses `crt.sh` and posts `%.tesla.com` and looks up certificate fingerprinting.

He mentions that `sublist3r` won't be able to deep find subdomains like `crt.sh` will (he then corrects himself at this is not true).

He mentions tomnomnom's `httprobe` to verify which domains are still alive.
