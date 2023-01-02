# Bandit Level 6 → Level 7
> ## Level Goal
>
>The password for the next level is stored somewhere on the server and has all of the following properties:
>
>    owned by user bandit7
>    owned by group bandit6
>    33 bytes in size
>
> ## Commands you may need to solve this level
>
> ls, cd, cat, file, du, find, grep

## How to solve this level



## Solution
```bash
bandit6@bandit:/$ find -size 33c -group bandit6 -user bandit7 -print 2>/dev/null
./var/lib/dpkg/info/bandit7.password

bandit6@bandit:/$ cat ./var/lib/dpkg/info/bandit7.password
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
```