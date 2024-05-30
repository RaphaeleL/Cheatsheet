# Emacs

> Raphaele Salvatore Licciardo, M.Sc.

## Text Navigation Beginner

- `C-f` Move forward a char
- `C-b` Move backward a char
- `M-f` Move forward a word
- `M-b` Move backward a word

- `C-v` Move forward a screen
- `M-v` Move backward a screen

- `C-p` Move to previous line
- `C-a` Move to beginning of line
- `C-e` Move to end of line

- `M-<` Start Multiple Cursors below 
- `M->` Start Multiple Cursors above

## Text Editing Beginner

- `BACKSPACE` Delete previous char
- `C-d` Delete next char
- `M-BACKSPACE` Kill (cut) previous word
- `C-/` Undo
- `C-x v` Copy
- `C-x p` Paste
- `C-x u` Undo
- `C-k` Delete rest of the line

## Text Navigation Intermediate

- `C-u6C-p` Move up 6 lines
- `C-u9C-b` Move backward 9 chars

- `C-u8C-f` Move forward 8 chars
- `C-u2C-b` Move backward 2 chars

- `C-u20w` Insert 20 'w's

## Text Editing

- `C-u20w` Insert 20 'w's

- `M-k` Kill (cut) to end of sentence
- `M-y` Previous yank
- `M-p` Move Text up
- `M-n` Move Text down

- `C-c c` Copy 
- `C-c p` Paste 
- `M-w` mark-word
- `M-a` mark-page
- `M-F` mark-defun
- `M-s` mark-paragraph

## File Management

- `C-xC-f` Find a file
- `C-x f` Find/Create File
- `C-xC-s` Save file
- `C-xC-b` List buffers
- `C-xb` Switch to buffer
- `C-xso` Save buffers
- `C-xk` Delete Buffer
- `C-xo` Switch Windows
- `C-x d` Dired
- `C-x m` Compile

## Windows 

- `C-x 2` Horizontal Split 
- `C-x 3` Vertical Split 
- `C-x o` Move around 
- `C-x 0` Close Split
- `C-x 1` Close all expect current 
- `C-x arrow` Move focus betweens plits 

## Misc

- `ESC ESC ESC` Get out of current command
- `C-xC-c` Close emacs
- `C-g` Stop command
- `C-s` Incremental search
- `C-xo` Change windows
- `M-C-v` Scroll other window
- `C-ha` Command apropos
- `C-c l` Buffer Menu
- `C-c k` Kill current Buffer
- `C <` Multi Line Command (add Line)
- `C >` Multi Line Command undo (remove Line)
- `C-tab` Next Buffer
- `C-S-tab` Previous Buffer
- `M-+` Increase Text Size
- `M--` Decrease Text Size
- `M-g g` Go-to Line

## Magit 

- `<Tab>` Preview Changes
- `s` git add <file>
- `cc` git add <file>
    - Type in the Commit Message, save and leave
- `pp` git push 
- `C-x g` Magit
- `S` Git add all
- `cc` Git Commit
- `C-c C-c` Leave Git Commit Message
- `Pp` Git push

## Dired

- `C  Compress
- `+` Create Dir
- `D` Mark to Delete
- `m` Mark
- `R` Rename, Move (if a file is marked)
- `C-ud` Delete a File
- `C-xC-f` Create a File

## Custom

### Dired
- `C-x d` dired 
- `C-x C-d` dired
- `C-x .` dired

### Magit
- `C-x g` magit-status
- `C-x C-g` magit-log-all

### Buffer Navigation
- `C-<tab>` next-buffer
- `C-<iso-lefttab>` previous-buffer
- `C-c l` ibuffer
- `C-c s` switch-to-buffer

### Window Navigation
- `C-x <left>` windmove-left
- `C-x <right>` windmove-right
- `C-x <up>` windmove-up
- `C-x <down>` windmove-down

### Close window
- `C-x 0` delete-window
- `C-x 1` delete-other-windows

### Usefull Commands
- `C-x m` compile
- `C-x c` shell-command
- `C-c n` duplicate-line
- `C-c d` delete-current-line
- `C-c j` join-line

### Copy and Paste
- `C-x v` simpleclip-copy
- `C-x p` simpleclip-paste
- `C-c C-c` simpleclip-copy
- `C-c C-v` simpleclip-paste
- `C-c c` simpleclip-copy
- `C-c v` simpleclip-paste

### Multi Cursor
- `C-<` mc/mark-next-like-this
- `C->` mc/mark-previous-like-this

### Font Size
- `M-+` text-scale-increase
- `M--` text-scale-decrease

### Kill Current Buffer
- `C-c k` kill-current-buffer

### Move Text
- `M-p` move-text-up
- `M-n` move-text-down

### Undo
- `M-z` undo

### Mark Whole Buffer
- `C-c a` mark-whole-buffer

### Magit
- `C-x g` magit

### Selection
- `M-w` mark-word
- `M-a` mark-page
- `M-F` mark-defun
- `M-s` mark-paragraph

### Line Numbers
- `C-x C-l` global-display-line-numbers-mode


