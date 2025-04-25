# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [original documentation](https://lazyvim.github.io/installation)
to get started if you do not want to install from this starter project.

## 🛠️ Installation

You can find a starter template for **LazyVim** [here](https://github.com/LazyVim/starter)

Install this [LazyVim Starter](https://github.com/beatzball/LazyVimStarter)

- Make a backup of your current Neovim files:

  ```sh
  # required
  mv ~/.config/nvim{,.bak}

  # optional but recommended
  mv ~/.local/share/nvim{,.bak}
  mv ~/.local/state/nvim{,.bak}
  mv ~/.cache/nvim{,.bak}
  ```

- Clone the starter

  ```sh
  git clone https://github.com/beatzball/LazyVimStarter ~/.config/nvim
  ```

- Remove the `.git` folder, so you can add it to your own repo later

  ```sh
  rm -rf ~/.config/nvim/.git
  ```

- Start Neovim!

  ```sh
  nvim
  ```

  Refer to the comments in the files on how to customize **LazyVim**.

## Tip

It is recommended to run `:LazyHealth` after installation.
This will load all plugins and check if everything is working correctly.
