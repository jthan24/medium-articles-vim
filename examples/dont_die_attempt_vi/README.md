# dont_die_attempt_vi

For check this repository you can read first this https://medium.com/@jthan24/learn-vim-and-dont-die-in-the-attempt-iv-char-jump-16daf5352944


## Go to line
```bash
gg   <-- Go to 1st line 
go   <-- Similar to gg
G    <-- Go to end line 
2G   <-- Go to the 2nd line
gm   <-- Go to center of the legible text
gM   <-- Go to center of the line
g0   <-- Go to the 1st position of the line
g$   <-- Go to the end of the line
g8   <-- Print the value of the current char in UTF-8
ga   <-- Print the value of the current char in ascii
gH   <-- Select the whole current line
```

## Remove char or a whole line
```bash
- Replace the content
rR
- Delete 
x
dw
d2w
dd
- Repeat last action
.
- Undo the previous action
u
```

## exit
For exiting from our VIM, we just neet enter :q! and press ENTER key, you return to your terminal


