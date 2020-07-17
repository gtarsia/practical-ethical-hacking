
# Enumerating HTTP/HTTPS part 2

The author uses a tool called `dirbuster` (also mentions `dirb` and `gobuster` as alternatives).

Runs that tool using a small list from a dirbuster directory in `/usr/share`.

While that runs, starts up burpsuite.

Meanwhile, he looks up the source code of the page to see any information disclosure,
yet founds nothing.

On burpsuite, he notices that by repeating requests, he gets information disclosure
about the OS and the software running it, which he types down on his notes.

Back to `dirbuster` results, he takes a look at some of the pages,
in one of them discovers that webalyzer 2.1 is being used
which he notes down alogn with a link and a screenshot to it.

Also notes down the results he got from running nikto and nmap.
