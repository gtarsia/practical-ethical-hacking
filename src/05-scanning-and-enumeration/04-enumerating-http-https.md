
# Enumerating HTTP/HTTPS

Author explains that the most usual ports vulns are ports 80, 139 and 445.

After having scanned the port of the kioptrix machine, it shows port 80 open.

Then author browsers that page and notices that he encounters a default apache page.

Author says to an attacker this means poor hygiene.

Then says this is the moment to start taking notes about this situation.

## Reading the default page

Author sees a link for documentation, tries to click it and gets a 404,

In this page we are given information about apache version, and about the hostname
internally. Author then writes this down in notes and instructs to get a screenshot of this.

This is what the author refers to as "information disclosure".

## Using nikto

Author says to be cautious of using `nikto` on a site with good security
because sometimes `nikto` gets blocked.

He runs `nikto -h <vm_ip>`, and then saves the results of this scan.

I saved my scan [here](./nikto_scan.txt)


