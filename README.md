# Also install

- bear (just `sudo apt-get install bear`)
- xclip 



Note on current kickstart.nvim:
- lazy.nvim is installed (https://hithub.com/folke/lazy.nvim.git)
- Plugins are installed in init.lua from row 160 (search for require('lazy').setup({...}))
- 

| Prerequisite                 | Command                                               | Function                                                 | Note                                |
| ---------------------------- | ----------------------------------------------------- | -------------------------------------------------------- | ----------------------------------- |
|                              | `<space>`                                             | Leader key                                               | To be used for personal keybindings |
| Be in search mode            | `n` or `Esc`                                          | Clear out highlights                                     |                                     |
| Be in split navigation       | `<C-h><C-k><C-j><C-l>`                                | Navigate between windows                                 | use `:help wincmd`                  |
| Searchmode <term> then Enter | # to go previous occurrence * to go next occurrence   | Go prev/next occurrence of `<term>` while in search mode |                                     |
| Normal mode                  | `grd` - Go to definition                              |                                                          |                                     |
| Normal mode                  | `grr` - Find references                               |                                                          |                                     |
| Normal mode                  | Ctrl+t                                                | Go back to previous file after grd (go to definition)    |                                     |
| Normal mode                  | - `grn` - Rename                                      |                                                          |                                     |
| Normal mode                  | - `gra` - Code actions                                |                                                          |                                     |
| Normal mode                  | - `K` - Hover documentation                           |                                                          |                                     |
| Search mode                  | `n` to go to next match, `N` to go back to prev match | After /searching  and getting a match, check them out    |                                     |

Installed:
	- lazy.nvim
	- gitsigns.nvim
	- which-key.nvim
	- telescope.nvim
	- lazydev.nvim
	- mason-tool-installer
	- mason-lspconfig
	- stevearc/conform.nvim (autoformat)
	- saghen/blink.cmp (autocompletion)
	- gruvbox.nvim
	- folke/todo-comments.nvim
	- echanovski/mini.nvim
	- nvim-treesitter/nvim-treesitter