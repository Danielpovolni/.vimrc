set number 
syntax on
set encoding=utf-8
set number relativenumber

" complile c++ and executing it
nnoremap <C-z> :!g++ -o %:r.out % -std=c++11<Enter>
nnoremap <C-x> :!./%:r.out

"setting tabs to be 4 spaces
set tabstop=4 softtabstop=4 shiftwidth=4

"executing vimrc in the same folder that file is 
set exrc

set guicursor=
"better search :/
set nohlsearch
set hlsearch
set incsearch

set wildmode=longest,list,full

"no bells after errors
set noerrorbells

"no wrap when number of characters passes window
set nowrap

"no swap file(boring error)
set noswapfile

set signcolumn=yes

"setting theme to dark
set bg=dark

"setting key for normal mode from esc to jk
imap jk <Esc>

"setting filetype
set filetype

"setting tabs to go verticaly
set splitbelow splitright

"Pluging with vim-plug
call plug#begin('~/.vim/plugged')
Plug 'gruvbox-community/gruvbox'
call plug#end()
