# Galaxy - Tabline

Galaxy-tabline is a fully-featured neovim status line that integrates a tabline [into the status line!].
It also supports a number of other features such as [`coc.nvim`](https://github.com/neoclide/coc.nvim) integration.

![image_2022-01-26-12-01-04](img/image_2022-01-26-12-01-04.png)


## Rationale
Have you ever taken a good look at your `vim` set up and realize that the status line leave a *lot* of unused space, especially in the statusline area?

For example, look at this statusline example in the galaxyline repo:
![](https://user-images.githubusercontent.com/60138143/103373409-8d131d00-4add-11eb-8dfc-40a37422f430.png)
That's a lot of wasted valuable vertical screen real estate. Why not put something useful in that space? 
Such as, for example, tabs?
This now frees up a ton of space in the actual tabline area for displaying more information such as [buffers](https://github.com/akinsho/bufferline.nvim) without it getting absurdly crowded.



## Usage/Installation

1. Clone the repo/download `galaxyline_config.lua`
2. Put it in your `.config/nvim/lua/` folder or wherever you want it to be.
3. `source` it in your `init.vim` file, i.e. `lua require('galaxyline_config')`

> Note: This plugin requires `nvim` > 0.5 and [galaxyline.nvim](https://github.com/NTBBloodbath/galaxyline.nvim)









