# vim-config
My personal vim configuration

## Contents

This vim configuration consists of some adjustments to .vimrc and the following plugins:

* ctrl-p: https://github.com/kien/ctrlp.vim.git
* neocomplete: https://github.com/Shougo/neocomplete.vim.git
* nerdtree: https://github.com/scrooloose/nerdtree.git
* python-mode: https://github.com/klen/python-mode.git
* tabman: https://github.com/kien/tabman.vim.git
* tagbar: https://github.com/majutsushi/tagbar.git
* vim-airline: https://github.com/bling/vim-airline
* IndexedSearch.vim: http://www.vim.org/scripts/script.php?script_id=1682
* NERD_commenter.vim: https://github.com/scrooloose/nerdcommenter
* tasklist.vim (a patched version to allow toggle): http://www.vim.org/scripts/script.php?script_id=2607 / https://github.com/vim-scripts/TaskList.vim

## Shortcuts

Most keyboard shortcuts are at their defaults. Here's what you will get with this .vimrc:

* ,o: python-mode lint code checker
* ,p: python-mode auto-PEP8 (automatically saves the file!)
* F8: tagbar toggle
* Ctrl-N: nerdtree toggle 
* F2: tasklist toggle
* F3: tabman show/focus
* <lead>mt: tabman show/hide

### Notes

You will need the patched fonts for airline to work properly, and a proper TERM. I'm using 'xterm-256color' and for the patched fonts, check vim-airline README (see above).
