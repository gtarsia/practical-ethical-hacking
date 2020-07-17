
# Scripting with bash

`cut` has a `-d` flag. The value after `-d` is a delimiter that is used to delimit text. 

Then `-f` for field, lets you obtain the n number using that delimiter.

So `cut -f " " -f 4` would take the word after the fourth space.

The `tr -d ":"` command removes the `:` from stdout of previous command.

## Iterating

`seq` gives us ability to use in a `for` loop.

We can also in shell run `for ip $(cat file); do command $ip & done` to iterate a file.

## Oneline shell iteration is important

It is very useful for some that does pentesting.
