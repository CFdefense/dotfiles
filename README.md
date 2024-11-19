# Dotfiles for Hyprland on Arch Linux

Welcome to my dotfiles repository! This repository contains my personal configuration files for a Hyprland setup on Arch Linux. These dotfiles include configurations for various tools and applications to help you get started with a similar setup.

## Demo

<div>
    <img src="https://github.com/CFdefense/CFdefense.github.io/blob/main/public/media/projects/hypr.gif?raw=true" alt="Description of the GIF" width="1000">
</div>

## Features

- **Hyprland Configuration**: Custom settings and themes for Hyprland.
- **Zsh Configuration**: Custom `.zshrc` for Zsh with useful aliases and settings.
- **Cava Configuration**: Custom settings for the Cava audio visualizer.
- **Hyde Configuration**: Custom settings for Hyde, including customizable themes for hyprland.
- **Rofi Configuration**: Custom settings for Rofi, a window switcher and application launcher.
- **Kitty Configuration**: Custom settings for Kitty, a fast and feature-rich terminal emulator.
- **Swaylock Configuration**: Custom settings for Swaylock, the lock screen for Sway, and Wayland configured for hyprland.
- **Waybar Configuration**: Custom settings for Waybar, a highly customizable Wayland bar.

## Installation

### Prerequisites

- Arch Linux installed
- Hyprland installed
- Zsh installed (optional, if you use Zsh)
- Cava installed
- Hyde installed
- Rofi installed
- Kitty installed
- Swaylock installed
- Waybar installed

### Setup

1. **Clone the Repository**

```bash
  git clone https://github.com/CFdefense/dotfiles.git
  cd dotfiles
```
   
2. **Install Dependencies**

  ```bash
    sudo pacman -S hyprland zsh neovim git cava hyde rofi kitty swaylock waybar
  ```
3. **Link Required Config Files**

  ```bash
    ln -sf ~/dotfiles/.config/hypr/hyprland.conf ~/.config/hypr/hyprland.conf
    ln -sf ~/dotfiles/.zshrc ~/.zshrc
    ln -sf ~/dotfiles/.config/cava/config ~/.config/cava/config
    ln -sf ~/dotfiles/.config/hyde/config ~/.config/hyde/config
    ln -sf ~/dotfiles/.config/rofi/config.rasi ~/.config/rofi/config.rasi
    ln -sf ~/dotfiles/.config/kitty/kitty.conf ~/.config/kitty/kitty.conf
    ln -sf ~/dotfiles/.config/swaylock/config ~/.config/swaylock/config
    ln -sf ~/dotfiles/.config/waybar/config ~/.config/waybar/config
  ```

Enjoy Hyprland
   
