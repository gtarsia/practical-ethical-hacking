
# Enumerating SSH

There's not a lot to this chapter.

Author tries to connect to ssh of Kioptrix.

He has to resort to using:

`ssh <ip> -oKexAlgorithms=+diffie-hellman-group1-sha1 -c aes128-cbc`

... because the key exchange algorithms and ciphers are old.

He doesn't try to login though, as he explains is part of exploitation.
