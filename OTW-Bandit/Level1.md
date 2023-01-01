# Bandit Level 0 → Level 1

>## Level Goal
>The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

>## Commands you may need to solve this level
>ls , cd , cat , file , du , find

## How to solve this level.


## Solution
```bash
bandit0@bandit:~$ pwd
/home/bandit0
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme 
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
```
