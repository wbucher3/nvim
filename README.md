# nvim 

Install Neovim

`sudo apt install neovim`

Put Config in `~/.config/`

`git clone --depth 1 -b main https://github.com/wbucher3/nvim.git`

Install Packer

`git clone --depth 1 https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim`

Finally, open Neovim with `nvim` and run `:PackerInstall` to install the packages
