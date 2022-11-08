# dont_die_attempt_vi

For check this repository you can read first this https://medium.com/@jthan24/learn-vim-and-dont-die-in-the-attempt-iv-char-jump-16daf5352944

Command related:

## Jump for characters
Highlight the numbers
```bash
:set nu<Enter>
```
Jump to the 4th line
```bash
:4<Enter>
$   <-- Jump to the end of the line
0   <-- Jump to the beginning of the line
```

## Find the occurrences
```bash
0    <-- for move on the beginning
ft   <-- for find the first t
4ft  <-- for find the 4th t
Ft   <-- for jump into the previous t
2Ft  <-- for jump into the 2 previous t
```

## Jump between brackets
```bash
:8<Enter>
<Shift>5    <-- for jump the first bracket
<Shift>5    <-- for jump the beginning bracket
```
If you repeat the key combination you stay in the loop in these brackets


## exit
For exiting from our VIM, we just neet enter :q! and press ENTER key, you return to your terminal


