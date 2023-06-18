My own variation of gruvbox colorscheme made with :love:.

# Screenshot

### dark mode

![dark mode](./assets/gruvbox.png)

# Installation

how to to install gruvbox.nvim with packer.nvim, vim-plug or lazy

[packer.nvim](https://github.com/wbthomason/packer.nvim)

```
use {
  'Zeddnyx/gruvbox.nvim',
}

```

[vim-plug](https://github.com/junegunn/vim-plug)

```
Plug 'Zeddnyx/gruvbox.nvim'
```

[Lazy](https://github.com/folke/lazy.nvim.git)

```
{
   "Zeddnyx/gruvbox.nvim",
   lazy = false,
   priority = 100,
   config = function()
     vim.cmd("colorscheme gruvbox")
   end
}
```

now set gruvboy.nvim as your default colorscheme in vimrc

if using init.lua

```
vim.cmd("colorscheme gruvbox")
```

if using init.vim

```
colorscheme gruvbox
```

# License

Source is available under the [Mit License](https://github.com/mnabila/gruvboy.nvim/blob/main/LICENSE)
