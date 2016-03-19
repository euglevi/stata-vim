Vim + Stata
===========

Syntax highlighting and snippets for editing Stata files with vim/neovim.


## Features

* Syntax highlighting for `.do` and `.ado` scripts.
* Syntax highlighting for `.dct` dictionary files (used with `infile`).
* Syntax highlighting for SMCL (Stata help files).
* Snippets for use with [UltiSnips](https://github.com/sirver/ultisnips).

My goal is to be compatible with the latest version of Stata, which is
currently Stata 14.


## Installation

### [vim-plug](https://github.com/junegunn/vim-plug)

Include the following in your `.vimrc` (vim) or `init.vim` (neovim):

```VimL
call plug#begin()
    Plug 'poliquin/stata-vim'
call plug#end()
```


### [Vundle](https://github.com/VundleVim/Vundle.vim)

Include the following in your `.vimrc` (vim) or `init.vim` (neovim):

```VimL
call vundle#begin()
    Plugin 'poliquin/stata-vim'
call vundle#end()
```


### [Pathogen](https://github.com/tpope/vim-pathogen)

Clone the repo to your `bundles/` directory:

```bash
cd ~/.vim/bundle
git clone git://github.com/poliquin/stata-vim.git
```


## Credits

* The main syntax file is mostly the work of [Jeff Pitblado](https://github.com/jpitblado/vim-stata).
* The SMCL syntax file is entirely from [Jeff Pitblado](https://github.com/jpitblado/vim-stata).
* Number highlighting group from [Zizhong Yan](https://github.com/zizhongyan/stata-vim-syntax)
