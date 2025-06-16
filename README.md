# My dotfiles

This repository contains the dotfiles for my system

## Requirements 

Following packages need to be installed on your system

### Required packages
```bash 
$ sudo apt install git
$ sudo apt install stow # https://www.youtube.com/watch?v=y6XCebnB9gs
```

## Instalation

First, clone the dotfiles repo in your $HOME directory using git

```bash
$ git clone https://github.com/Billypl/dotfiles
$ cd dotfiles
```
then use GNU stow to create symlinks
```bash
$ stow .
```

