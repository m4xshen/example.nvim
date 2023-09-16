# example.nvim

An example plugin that map `<Leader>h` to say hello.

## 📦 Installation

1. Install via your favorite package manager.

```Lua
-- lazy.nvim
{
   "m4xshen/example.nvim",
   opts = {}
},
```

2. Setup the plugin in your `init.lua`. This step is not needed with lazy.nvim if `opts` is set as above.

```Lua
require("example").setup()
```

## 🚀 Usage

Press `<Leader>h` and it says hello to you.

## 🔧 Configuration

You can pass your config table into the `setup()` function or `opts` if you use lazy.nvim.

### Options

- name (type: string): the name that example.nvim greets with
