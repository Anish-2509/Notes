## This is a demo note, written in neovim.
Basic keybindings for neovim: 
`Esc`: Navigate 
`i`: Insert to type/edit before character 
`v`: Select text 
`:`: Run commands 
`a`: Insert after the character 
`I`: Insert at the start of the line
`A`: Insert at the end of the line

# Neovim Learning Notes

## Date: 2025-06-24

### Concepts Learned Today:

- Neovim has different **modes** (Normal, Insert, Visual, Command)
- `i` inserts **before** cursor, `a` inserts **after**
- `dw` deletes from cursor to start of next word
- `diw` deletes only the **inner word** (handy)


---

- `G` takes you to the last line.
- `gg` takes you to the first line
- `:n` where n is a number, takes you to the specific line number
- `H` top of the screen
- `M` middle of the screen
- `L` bottom of the screen
- `Ctrl d` scroll down half a page
- `Ctrl u` scroll up half a page
- `Ctrl f` scroll forward(full page)
- `Ctrl b` scroll back(full page)
- `w` move to start of next word
- `e` move to the end of current/next word
- `b` move to the start of previous word

---

- `^` Start of line
- `0` Beginning of line(column 0)
- `$` End of line(last character)

---

- `dd` is to delete a line
- `dw` delete the word infront of cursor
- `d$` delete till end of line
- `x` delete the character under the cursor
- `X` delete a character before the cursor

---

- `u` Undo
- `Ctrl r` Redo
- `yy` yank/copy to vim interface
- `"+yy` yank/copy to system clipboard
- `d` to cut and `p` to paste(here all the delete commands can be use for cut)

---

- `/` search from start
- `?` search from end
- `:noh` remove search highlights
- `%s/old_word/new_word` to replace the highlighted search word and add `/g` at the end to replace all

