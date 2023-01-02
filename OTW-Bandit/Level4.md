# Bandit Level 3 → Level 4
> ## Level Goal
>
>The password for the next level is stored in a hidden file in the inhere directory.
> ## Commands you may need to solve this level
>
> ls, cd, cat, file, du, find

## How to solve this level
ls with the argument "-a" of "-all".

## Solution
```bash
bandit3@bandit:~/inhere$ ls -a
.  ..  .hidden
bandit3@bandit:~/inhere$ ls -all
total 12
drwxr-xr-x 2 root    root    4096 May  7  2020 .
drwxr-xr-x 3 root    root    4096 May  7  2020 ..
-rw-r----- 1 bandit4 bandit3   33 May  7  2020 .hidden
bandit3@bandit:~/inhere$ find

bandit3@bandit:~/inhere$ cat .hidden 
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
```