## Basics

| Action              | Shortcut      |
| ------------------- | ------------- |
| Enter insert mode   | `i`           |
| Exit insert mode    | `<Esc>`       |
| Save                | `:w`          |
| Quit                | `:q`          |
| Save & Quit         | `:wq` or `ZZ` |
| Quit without saving | `:q!`         |

## File Navigation 

| Action                       | Shortcut       |
| ---------------------------- | -------------- |
| **Search files (Telescope)** | `<leader> s f` |
| Live grep (search in files)  | `<leader> s g` |
| Search open buffers          | `<leader> s b` |
| Help tags search             | `<leader> s h` |
| Resume last Telescope picker | `<leader> s r` |

## Buffers & Windows

| Action                    | Shortcut            |
| ------------------------- | ------------------- |
| List buffers              | `:ls`               |
| Switch buffer             | `:b<number>`        |
| Close current buffer      | `:bd`               |
| Split window (horizontal) | `:split` or `:sp`   |
| Split window (vertical)   | `:vsplit` or `:vsp` |
| Move between windows      | `<C-w> h/j/k/l`     |

## Editing & Movement

| Action                 | Shortcut |
| ---------------------- | -------- |
| Delete line            | `dd`     |
| Copy line              | `yy`     |
| Paste below            | `p`      |
| Undo                   | `u`      |
| Redo                   | `<C-r>`  |
| Move by word           | `w`, `b` |
| Jump to line start/end | `^`, `$` |

## LSP (Language Server Protocol)

| Action           | Shortcut       |
| ---------------- | -------------- |
| Show hover info  | `K`            |
| Go to definition | `gd`           |
| Go to references | `gr`           |
| Rename symbol    | `<leader> c r` |
| Code actions     | `<leader> c a` |
| Format document  | `<leader> f`   |

## Tools

| Action                   | Shortcut     |
| ------------------------ | ------------ |
| Open Lazy.nvim plugin UI | `<leader> l` |
| Open Mason UI (LSP mgr)  | `<leader> m` |
| Open file tree (netrw)   | `:Ex`        |

## Visual Mode

| Action                                              | Shortcut              |
| --------------------------------------------------- | --------------------- |
| Enter visual mode                                   | `v`                   |
| Enter visual line mode                              | `V`                   |
| Enter block (column) mode                           | `<C-v>`               |
| Indent selection right                              | `>`                   |
| Indent selection left                               | `<`                   |
| Comment selection (with plugin like `Comment.nvim`) | `gc` (in visual mode) |
| Yank selection                                      | `y`                   |
| Delete selection                                    | `d`                   |
| Paste over selection                                | `p`                   |

## Telescope Extensions (like ui-select, projects)

| Extension   | What it does                            | Shortcut *(if mapped)*       |
| ----------- | --------------------------------------- | ---------------------------- |
| `ui-select` | Makes code actions, etc., use Telescope | Used automatically           |
| `projects`  | Switch between Git projects             | `<leader> s p` *(if mapped)* |
| `frecency`  | Sort files by recency + frequency       | Not in Kickstart by default  |

## Macros

| Action                            | Shortcut        |
| --------------------------------- | --------------- |
| Start recording into register `a` | `qa`            |
| Do stuff…                         | (your commands) |
| Stop recording                    | `q`             |
| Replay macro from `a`             | `@a`            |
| Repeat last macro                 | `@@`            |
