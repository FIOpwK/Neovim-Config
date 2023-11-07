# Neovim-Config
neovim configuration
set mouse=a
set number
set hidden
set cursorline
set expandtab
set autoindent
set smartindent
set shiftwidth=4
set tabstop=4
set encoding=utf8
set history=5000
set clipboard=unnamedplus

call plug#begin('~/.config/nvim/plugged')

"Plugins
Plug 'preservim/nerdtree'
Plug 'vim-airline/vim-airline-themes'
Plug 'https://github.com/morhetz/gruvbox'
Plug 'https://github.com/jiangmiao/auto-pairs'
Plug 'https://github.com/preservim/nerdcommenter'
Plug 'https://github.com/norcalli/nvim-colorizer.lua'
Plug 'https://github.com/vim-airline/vim-airline-themes'
Plug 'https://github.com/sirver/ultisnips'


call plug#end()

let g:AutoPairsFlyMode = 0
let g:AutoPairsShortcutBackInsert = '<M-b>'
let g:airline#extensions#tabline#enabled = 1
