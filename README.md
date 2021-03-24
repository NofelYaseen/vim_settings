# VIM settings

Here is my vim configuration file and with some instructions/commands I use regularly. It's beginner friendly so feel free to copy.

## Instructions

Copy `vimrc` file to `$HOME`. Rename it to `.vimrc`. 
This file contains all the plugins and settings. It's good to learn how to edit this file.

`Vundle` is a plugin manager for vim.  
`Vundle` let's you specify a plugin in a number of formats, but my favorite allows you to grab plugins straight off of github, just specify the bundle in the following format:
```
Bundle 'githubUsername/repoName'
```

Vundle setup instructions

```
mkdir .vim
cd .vim
mkdir bundle
cd bundle
git clone https://github.com/gmarik/vundle
```

## Commands

Install plugins from terminal: `vim +PluginInstall +qall`  

Vim cheatsheet: [here](http://www.viemu.com/vi-vim-cheat-sheet.gif)

These commands are in normal/command mode usless specified

Split screen: `:vsp <filename>`

Swap screens: `<C-w> <C-r>`

Move around screen: `<C-w> <C-direction>`, where direction - h,j,k,l

Goto line: `:<line_number>`

Comment/Uncomment line: `gcc`

Go to Start of file: `gg`

Go to end of line: `$`

Duplicate line: `yyp`
