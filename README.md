go-ide
===

![Neovim Gopher](https://raw.githubusercontent.com/plentiform/go-ide/master/gopher.png)

## Description

This project is a lightweight, [Neovim](https://neovim.io/) integrated development environment (IDE) for [Golang](https://golang.org/) development.

## Prerequisites

1. Install neovim: https://github.com/neovim/neovim/wiki/Installing-Neovim
2. Install vim-plug: https://github.com/junegunn/vim-plug#installation

## Installation

1. ~/.config/nvim/init.vim

## Features

- File browser: `nt`
- File search: <kbd>Ctrl</kbd>-`f`
- Text search: `/` then type your search terms (find terms <kbd>Enter</kbd>, next `n`, previous `N`, clear highlight <kbd>Ctrl</kbd>-`l`)  
- Go to definition: `gd` (traverse back with <kbd>Ctrl</kbd>-`o`)
- Method and property completion (cycle forward: <kbd>Tab</kbd>, cycle backward <kbd>Shift</kbd>-<kbd>Tab</kbd>, select <kbd>Enter</kbd>)
- Snippets / shortcuts (next input <kbd>Ctrl</kbd>-`j`, previous input <kbd>Ctrl</kbd>-`k`)
- Debugger
- Auto imports and tab formatting