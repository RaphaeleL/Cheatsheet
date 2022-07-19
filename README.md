# VimCheatsheet

Cheatsheet for the basic Vim Commands

> this is normaly enough. Type `vimtutor` for more. 

## Modes 

- Insert Mode: Entering with `i`
- Visual Mode: Entering with `v`
- Command Mode: Entering with `:` 
- Replace Mod: Entering with `:s`

## Moving around 

- `h` Moving the Cursor to the left
- `l` Moving the Cursor to the right
- `k` Moving the Cursor up
- `gk` Moving the Cursor up even in line-breaks
- `j` Moving the Cursor down
- `gj` Moving the Cursor down even in line-breaks
- `b` Moving the Cursor one Word back
- `Xb` Moving the Cursor X Word back
- `w` Moving the Cursor one Word forward
- `Xw` Moving the Cursor X Words forward
- `gg` Moving the Cursor to the Beginning of the File
- `G` Moving the Cursor to the End of the File
- `0` Moving the Cursor to the Beginning of the Line
- `$` Moving the Cursor to the End of the Line
- `A` Moving the Cursor to the End of the Line in Insert Mode
- `:abc` Go to the Line Number abc 
- `L` Go to the last Line on Screen 
- `M` Go to the last Middle on Screen 
- `(` Go to the previous Sentence 
- `)` Go to the next Sentence 
- `>` Indent 
- `<` Unindent 

## Edit Text 

- `rX` Replace the current Character with an X
- `x` Deletes the current Character
- `dw` Deletes the current Word
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

## Exit Vim 

- `:q!` Force to Exit
- `:q` Exit
- `:wq` Write and Exit
- `:wq` Write and Exit with Force

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

> this is normaly enough but (Vim) Regular Expressoins are like Rocket Science to me, so see [this](http://www.vimregex.com/) for more. 

- `^#` Match the Character # 
- `\(` Start a Group 
- `\)` End a Group 
- `.\{-}\` Match any character 0 or more times in a non-greedy way 
- `.\{.*}\` Match as little as possible, and not as much as possible 
- `abc` Match abc 
