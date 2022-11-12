# Dotfiles Repo
This is a repo to store my current config files. It would help me to
transfer my config file to other machines easily.

This is a work in progress. As time would progress I would keep
uploading my config file and setup steps. Later on though I plan to
create a script that would automate the whole process.

## How to setup the machine
### 1. Clone this repo
### 2. Install the **required packages**
#### A. Starship
The cross-shell prompt for astronauts
Arch: sudo pacman -S starship
### 3. Create the symlinks
#### A. Starship
ln -s ~/.dotfiles/starship.toml ~/.config/starship.toml