## Initial Setup

git clone https://github.com/radioramble/dotvim.git ~/.vim
ln -T -s ~/.vim/vimrc ~/.vimrc

## Usage

### My Tips

`:hi Normal ctermbg=none` fo transparent background

### Airline


### CtrlP

* run :CtrlP [starting-directory] to invoke CtrlP in find file mode in a particular directory
* <f5> clear CtrlP cache
* <tab> autocomplete directory
* <c-f> and <c-b> cycles between file mode, buffer mode, and most recently used mode
* <c-d> to switch to filename only search instead of full path
* <c-t> open in new tab
* <c-v> open in vertical split
* <c-x> open in horizontal split
* <c-n>, <c-p> to select the next/previous string in the prompt's history
* <c-y> to create a new file and its parent directories
* <c-z> to mark/unmark multiple files and <c-o> to open them
* or use <c-o> on it's own to be given option on how to open
* submit two or more dots .. to go up the directory tree by one or multiple levels
* type :diffthis before <c-o> when opening multiple files to run :diffthis on the first 4 files


### Emmet


### Fugitive


### Goyo


### Html 5 Omnicomplete and Syntax


### Hybrid Color Scheme


### Limelight


### Markdown Folding

* :FoldToggle switches between stacked and nested folding styles (default is stacked)
* zo -> open current fold
* zO -> recursively open current fold
* zc -> close curent fold (if the current fold is already closed, then it will close the parent fold)
* zC -> recursively close current fold
* za -> toggle a fold open/closed (mapped to <Space> in my vimc)
* zr -> reduce (open) folding (increase foldlevel by 1)
* zR -> open all
* zm -> more (close) folding (reduce foldlevel by 1)
* zM -> close all
* zn -> disable folding
* zN -> bring back folding as it was
* zi -> toggles between the two
* zj -> move down to top of next fold
* zk -> move up to bottom of previous fold

### Mustache Handlebars Mode


### Surround


### Syntastic

