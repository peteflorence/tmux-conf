# Tmux conf (by Pete)

---

## About

This tmux conf file tries to replicate some `terminator`-esque features in tmux, albeit imperfectly.

Definitely some inspiration from [here.](https://lukaszwrobel.pl/blog/tmux-tutorial-split-terminal-windows-easily/)

## Install

```
git clone https://github.com/peteflorence/tmux-conf.git
cd tmux-conf
./install.sh
```

## Cheatsheet

| cmd           | what           | note  |
| ------------- |-------------| -----:|
| tmux      | start tmux | prefer tmux a if anything was running |
| tmux a    | go back to what working on      |    |
| ctrl+b    | shortcut to everything in tmux |  |
| tmux ls | list sessions in tmux | |
| ctrl+b, :new | create new session | then name it |
| ctrl+b, $ | rename current session | |
| ctrl+b, s | switch session | |
| ctrl+b, alt+arrow | switch pane | | 
| ctrl+b, ctrl+e | split pane v**E**rtically | | 
| ctrl+b, ctrl+o | split pane h**O**rizontally | | 
| ctrl+b, d | detach | use this |
| ctrl+d | kill either a pane or window | | 

