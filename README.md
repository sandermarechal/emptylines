EmptyLines
==========

A quick VIM plugin for adding/removing empty lines around code.
Install it using Vundle. Example configuration:

    nnoremap <silent> <Up> :call DelEmptyLineAbove()<CR>
    nnoremap <silent> <Down> :call AddEmptyLineAbove()<CR>
    nnoremap <silent> <C-Up> :call DelEmptyLineBelow()<CR>
    nnoremap <silent> <C-Down> :call AddEmptyLineBelow()<CR>
