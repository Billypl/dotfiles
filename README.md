# My doftiles

This repository contains the dotfiles for my system

## Requirements 

Following packages need to be installed on your system

### Git
``` 
$ sudo apt install git
```
### Stow
```
$ sudo apt install stow
```

## Instalation

First, clone the dotfiles repo in your $HOME directory using git

```
$ git clone https://github.com/Billypl/dotfiles
$ cd dotfiles
```
then use GNU stow to create symlinks
```
$ stow .
```

