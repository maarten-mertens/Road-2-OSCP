# Bandit Level 4 → Level 5
>## Level Goal
>
>The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is >messed up, try the “reset” command.
> ## Commands you may need to solve this level
>
>ls, cd, cat, file, du, find

## How to solve this level


## Solution
bandit4@bandit:~/inhere$ find .| xargs file
.:         directory
./-file08: data
./-file06: data
./-file01: data
./-file02: data
./-file05: data
./-file07: ASCII text
./-file09: data
./-file00: data
./-file03: data
./-file04: data

bandit4@bandit:~/inhere$  cat ./-file07
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR