# example.nvim

An example plugin that says hello when you press `<Leader>h`

## 📦 Installation

1. Install via your favorite package manager.

```lua
-- lazy.nvim
{
   "m4xshen/example.nvim",
   opts = {}
},
```

2. Setup the plugin in your `init.lua`. This step is not needed with lazy.nvim if `opts` is set as above.

```lua
require("example").setup()
```

## 🚀 Usage

Press `<Leader>h` and it says hello to you.

## 🔧 Configuration

You can pass your config table into the `setup()` function or `opts` if you use lazy.nvim.

### Options

- name (optional, type: string): the name that example.nvim greets with

Example:

```lua
require("example").setup({
   name = "Max",
})
```
