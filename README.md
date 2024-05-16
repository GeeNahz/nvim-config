# My neovim lua configuration settings

This is the setup, written in lua language, for my neovim. It tranforms my neovim into a sort of IDE.

## Setup
### Installation
- Install Neovim from the system's package manager repository. Ensure the version of Neovim is >= v0.9.5. For more information about the installation, [click here](https://github.com/neovim/neovim/blob/master/INSTALL.md)
### Configuration
- Navigate into the config directory within the home directory using ```sh cd ~/.config```
- Clone this repo or download it to your machine.
  - If cloning the repo, use the following command ```sh git clone git@github.com:GeeNahz/nvim-config.git nvim```. This will clone the repo into a directory called ```sh nvim```.
  - If downloading the repo, create a directory called ```sh nvim``` within the ```sh ~/.config``` directory and copy the extracted files into the nvim directory.
    > The directory convention for the configuration files: ```sh ~/.config/nvim``` is because of Neovim's runtime path where it look for things to source in lua or other config files. Specifically for .lua files, the convention is to have things in ```sh ~/.config/nvim```. So anything within this directory will be loaded by Neovim and for lua, anything within ```sh init.lua``` gets loaded.
