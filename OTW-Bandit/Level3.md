# Bandit Level 2 → Level 3
>## Level Goal
>
> The password for the next level is stored in a file called spaces in this filename located in the home directory
> ## Commands you may need to solve this level
>
> ls, cd, cat, file, du, find
> ## Helpful Reading Material
>
>  Google Search for “spaces in filename”

## How to solve this level.
The easiest way to open a filename with spaces is to use apostrophes ("), quotation marks ('), or escape character (&#92;)

## Solution
```bash
bandit2@bandit:~$ cat spaces\ in\ this\ filename 
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

bandit2@bandit:~$ cat "spaces in this filename" 
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

bandit2@bandit:~$ cat 'spaces in this filename' 
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
```