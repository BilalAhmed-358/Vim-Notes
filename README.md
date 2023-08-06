## This repo contains my notes when I was learing to use Vim

- Vim has normally has 2 modes
  - Normal mode
  - Insert mode

**NORMAL MODE**
- Normal mode is already activated when you open a file
- You can activate "Insert mode" by pressing the `i` key on the keyboard
- When in the Insert mode you can edit the file and save and exit it.

**EXITING VIM**

- To exit the vim editor we use the `:q` command
- To save and exit the file we use the `:wq` command
- The `!` symbol in vim commands is used to force things, kinda like the `--force` flag in github.

**Moving around in vim**

- When in normal mode you use the `h,j,k and l` keys to move around
- we use the h key to move `left`
- we use the l key to move `right`
- we use the j key to move down one line
- we use the k key to move up one line
- to reach the next sentence we use the `shift  + 0` OR `)` symbol
- to reach the previous sentence we use the `shift  + 9` OR `(` symbol
- `w` will move to the beggining of the next word
- `e` will move to the end of the current word


**Searcing in vim**

- In normal mode write the `/` and write whatever you want to search after that
- Once you press enter you will enter search mode
- if you press `n` vim will take you to the next occurence of the word
- if you press `N` vim will take you to the previous occurence of the word
- `/` is the forward search command in vim
- `?` is the backward search command in vim
- if you don't know the correct spelling of the word you can enter `.` in the place of the letter.
- For Example: I want to search `wonderful` in the file, but I only know that letters `won` and `ful`, therefore for the missing letters `der` I will search like `/won...ful` and vim will match me with the word `wonderful`.


**Screen Movement**

- To get to the end of the file press `shift + g` or `G`
- To get to the start of the file press `gg`(g two times)
- To get the next page press `ctrl + f`
- To get the previous page press `ctrl + b`