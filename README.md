# sib (Start in Background)
A very simple script to start any* Linux GUI application in a terminal, in the background, silently, and completely detached from said terminal.

### I do not take any credit for anything other than putting this in a script. This solution was originally found in [this article on Tecmint](https://www.tecmint.com/run-linux-command-process-in-background-detach-process/), which was authored by [Aaron Kili](https://www.tecmint.com/author/aaronkili/). 

## Usage
`sib [program you'd like to start here]`
This script only takes a single argument, which is the program you would like to start.

## Installation
**Note that I have only tested this on Linux Mint, and do not currently intend to test it elsewhere. Your results may vary.**
I recommend making a directory called `bin` in your home folder and putting sib in there (i.e. `\home\ann\bin\sib`). This will allow you to use sib without specifying a path every time, or messing about with symlinks and $PATH and whatnot.

## \*
*I have tried this with a number of applications on my system (Firefox, Chromium, Remmina, nemo, and so on) and it has worked flawlessly. However, I cannot guarantee it will work with everything. I would encourage trying to start the program in the terminal on its own first, outside of sib, to make sure it works properly beforehand.*
