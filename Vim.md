# Vim

Cheatsheet for the basic Vim Commands

> Raphaele Salvatore Licciardo, B.Sc.

## Modes

- Insert Mode: Entering with `i`
- Visual Mode: Entering with `v`
- Command Mode: Entering with `:`
- Replace Mod: Entering with `:s`

- Theoretically there are more Modes like `x` and `-y` but they are ugly. So don't use them!

## Moving around

- `^d` Moving a Page down
- `^u` Moving a Page up
- `h` Moving the Cursor to the left
- `l` Moving the Cursor to the right
- `k` Moving the Cursor up
- `o` Adding a line below in Insert Mode
- `gk` Moving the Cursor up even in line-breaks
- `j` Moving the Cursor down
- `gj` Moving the Cursor down even in line-breaks
- `b` Moving the Cursor one Word back
- `Xb` Moving the Cursor X Word back
- `w` Moving the Cursor one Word forward
- `Xw` Moving the Cursor X Words forward
- `Xj` Moving the Cursor X lines down
- `Xk` Moving the Cursor X lines up
- `Xh` Moving the Cursor X chars left
- `Xl` Moving the Cursor X chars right
- `gg` Moving the Cursor to the Beginning of the File
- `G` Moving the Cursor to the End of the File
- `0` Moving the Cursor to the Beginning of the Line
- `$` Moving the Cursor to the End of the Line
- `:abc` Go to the Line Number abc
- `H` Go to the last Middle on Screen
- `M` Go to the last Middle on Screen
- `L` Go to the last Line on Screen
- `(` Go to the previous Sentence
- `)` Go to the next Sentence
- `>` Indent
- `<` Unindent
- `O` Insert a line above with Insert Mode
- `o` Insert a line below with Insert Mode
- `I` moves the cursor to the beginning of the line with Insert Mode
- `A` moves the cursor to the end of the line with Insert Mode
- `i` moves the cursor to the beginning of the character with Insert Mode
- `i` moves the cursor to the end of the character with Insert Mode
- `fx` moves to the first Character `x`
- `Fx` moves to the first Character `x` backwards
- `tx`ves to the first Character `x` but not on it, just before
- `Tx` moves to the first Character `x` but not on it, just before, backwards
- `,` do it again backwards
- `;` do it again forwards
- `gf` Jumps to an File (e.g. Open an Imported File -> import "path/to/file.lua")

## Edit Text

- `=` Align Selection
- `u` Make Selection Lowercase
- `U` Make Selection Uppercase
- `rX` Replace the current Character with an X
- `x` Deletes the current Character
- `x` Deletes the current Character
- `dw` Deletes the current Word from the actuall position
- `ciw` Deletes the current Word
- `db` Deletes until Beginning
- `ce` Deletes the current Word and go to Insert Mode
- `dXw` Deletes the next X Words
- `dd` Deletes the current Line
- `:x,yd` Deletes Line x to y
- `d\$` Deletes the current Line from the actual position
- `C` Deletes the current Line from the actual position and go to Insert Mode
- `ce` Deletes the current Line from the actual position and go to Insert Mode
- `D` Deletes the current Line from the actual position
- `J` Join current Line with the next Line
- `P` Put Buffer befor cursor
- `p` Put Buffer after cursor
- `gU` Uppercase
- `gu` Lowercase
- `df(` delete everything until the `(` Character
- `dt(` delete everything before the `(` Character
- `dF(` delete everything until the `(` Character but backwards
- `dT(` delete everything before the `(` Character but backwards
- `d,` do it again backwards
- `d;` do it again forwards
- `yf(` yank everything until the `(` Character
- `yt(` yank everything before the `(` Character
- `yF(` yank everything until the `(` Character but backwards
- `yT(` yank everything before the `(` Character but backwards
- `y,` do it again backwards
- `y;` do it again forwards
- `vf(` select everything until the `(` Character
- `vt(` select everything before the `(` Character
- `vF(` select everything until the `(` Character but backwards
- `vT(` select everything before the `(` Character but backwards
- `v,` do it again backwards
- `v;` do it again forwards
- `da)` Delete around Brackets 
- `da}` Delete around Curly Brackets 
- `dap` Delete around Paragraph 
- `vaw` Visually select around word 

## Exit Vim

- `:q!` Force to Exit
- `:q` Exit
- `:wq` Write and Exit
- `:wq` Write and Exit with Force

### Delete

- `dl` delete character (alias: `x`)
- `diw` delete inner word
- `daw` delete a word
- `diW` delete inner WORD (see |WORD|)
- `daW` delete a WORD (see |WORD|)
- `dgn` delete the next search pattern match
- `dd` delete one line
- `dis` delete inner sentence
- `das` delete a sentence
- `dib` delete inner '(' ')' block
- `dab` delete a '(' ')' block
- `dip` delete inner paragraph
- `dap` delete a paragraph
- `diB` delete inner '{' '}' block
- `daB` delete a '{' '}' block

## Search and Replace

- `/abc` Search for abc in the Document
- `n` Go to the next Result
- `N` Go to the previous Result
- `:noh` Stop Highlighting the Results
- `:%s/foo/bar` Search in the complete Document for foo and replace it with bar
- `:%s/foo/bar/g` Search in the complete Document for foo and replace it with bar, for every result!
- `:'<,'>s/foo/bar` Search in the actual selection for foo and replace it with bar!
- `:'<,'>s/foo/bar/g` Search in the actual selection for foo and replace it with bar, for every result!

### Regular Expressions

> this is normaly enough, but see [this](http://www.vimregex.com/) for more.

- `^#` Match the Character #
- `\(` Start a Group
- `\)` End a Group
- `.\{-}\` Match any character 0 or more times in a non-greedy way
- `.\{.*}\` Match as little as possible, and not as much as possible
- `abc` Match abc

### Netrw 

- `%` Open a new file in netrw's current directory
- `d` Make a directory
- `D` Attempt to remove the file(s)/directory(ies)
- `p` Preview the File
- `R` Rename the designated file(s)/directory(ies)
- `-` Makes Netrw go up one directory
