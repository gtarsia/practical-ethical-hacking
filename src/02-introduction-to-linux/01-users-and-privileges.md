
# Users and privileges

When running `ls -la`

At the start of the file you get

`drwxrwxrwx`

Any of these chars can show up replaced with a hyphen char `-`.

`-r-xr-xrw-`

The first char represents the type of a file.

If it's a `d` it's a directory, if it's a `-` it's a normal file.

Then comes three groups of chars, each group is made of `rwx`, and each can be replaced by a hyphen. `r` stands for read, `w` stands for write, and `x` stands for execute.

## /etc/shadow file

This file has passwords so with it we can crack the passwords of a user.
