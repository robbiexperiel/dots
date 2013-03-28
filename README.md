dots
====

A collection of dotfiles.

Installation
------------

The installation script requires `zsh`, so install that and set it as your shell first. You can then download and run the script using either `curl` or `wget`.

The script will clone this repository and its submodules, then symlink all the files into the right places.

### Using `curl`

`curl -L https://github.com/robbiemc/dots/raw/master/install.zsh | zsh`

### Using `wget`

`wget --no-check-certificate https://github.com/robbiemc/dots/raw/master/install.zsh -O - | zsh`
