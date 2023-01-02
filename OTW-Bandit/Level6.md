# Bandit Level 5 → Level 6
> ## Level Goal
>
>The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
>
>human-readable
>1033 bytes in size
> not executable
>
> ## Commands you may need to solve this level
>
> ls, cd, cat, file, du, find

## Solution
```bash
bandit5@bandit:~$ cat | find . -size 1033c
./inhere/maybehere07/.file2
cat ./inhere/maybehere07/.file2
bandit5@bandit:~$ cat ./inhere/maybehere07/.file2 
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
```