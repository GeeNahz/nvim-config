# My neovim lua configuration settings

This is the setup, written in lua language, for my neovim. It tranforms my neovim into a sort of IDE.

## Setup
### Installation
- Install nvim from the system's package manager repository. Ensure the version of neovim is >= v0.9.5. For more information about the installation, [click here](https://github.com/neovim/neovim/blob/master/INSTALL.md)
### Configuration
- Clone this repo or download it to your machine.
- Create a directory ```bash /nvim``` for the configuration files in the home directory. Use the following command to create the directory as per convention ```bash mkdir ~/.config/nvim```.
  > This is because of Neovim's runtime path where it look for things to source in lua or other config files. Specifically for .lua files is to have things in ```bash ~/.config/nvim```. So anything within this directory will be loaded by Neovim and for lua, anything within ```bash init.lua``` gets loaded.
- Move/copy the cloned/downloaded files to the ```bash ~/.config/nvim``` directory.
