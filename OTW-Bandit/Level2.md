# Bandit Level 1 → Level 2
> ## Level Goal
>The password for the next level is stored in a file called - located in the home directory
> ## Commands you may need to solve this level
>
> ls, cd, cat, file, du, find
> ## Helpful Reading Material
> Google Search for “dashed filename”
> Advanced Bash-scripting Guide - Chapter 3 - Special Characters

## How to solve this level.
The approach of previous level does not work, the command ```bash cat - ``` gives no output.
The dash (-) is used in terminal to pass parameters.
You can open the file by pointing to the path ```bash ./-```


## Solution
```bash
bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat -
^C
bandit1@bandit:~$ cat ./-
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
```
