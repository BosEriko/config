# Config
This is my personal config for Windows 11. Feel free to use it or fork it.

## Installation Scripts
The config is divided into parts for modularity:
- [Package Manager](https://github.com/BosEriko/scoop.git) - Includes Scoop
- [Hotkeys](https://github.com/BosEriko/powertoys.git) - Includes PowerToys
- [Window Manager](https://github.com/BosEriko/glaze.git) - Includes GlazeWM
- [Editor & Terminal](https://github.com/BosEriko/vs.git) - Includes Visual Studio Code
- [Virtual Machine](https://github.com/BosEriko/wsl.git) - Includes WSL
- [Shell](https://github.com/BosEriko/zsh.git) - Includes ZSH, Oh My ZSH and Git Configuration
- [Distro](https://github.com/BosEriko/nix.git) - Includes NixOS Configuration, Flakes, Home Manager, etc.

## Clone the repository
To start you must first clone the repository. Run the command below on NixOS on WSL to clone the repository.
``` sh
git clone --recurse-submodules https://github.com/BosEriko/config.git ~/config
```
