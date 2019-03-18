# Xander's Dotfiles

A bunch of garbage that I use to pretend it makes me faster in a command line.

## Installation

```sh
# Install stow if you haven't already.
sudo apt-get install stow # On Ubuntu
brew install stow # On OSX

# Basic Installation
git clone https://github.com/freerunningtech/dotfiles
cd dotfiles
git submodule init
git submodule update
./install.sh
vim +PluginInstall +qa
```
