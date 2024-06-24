# Config
This is my personal config for Windows 11. Feel free to use it or fork it.

## Installation Scripts
The config is divided into parts for modularity:
- [Package Manager](https://github.com/BosEriko/scoop.git) (scoop) - Includes Scoop
- [Hotkeys](https://github.com/BosEriko/powertoys.git) (powertoys) - Includes PowerToys
- [Window Manager](https://github.com/BosEriko/glaze.git) (glaze) - Includes GlazeWM
- [Editor & Terminal](https://github.com/BosEriko/vs.git) (vs) - Includes Visual Studio Code
- [Virtual Machine](https://github.com/BosEriko/wsl.git) (wsl) - Includes WSL
- [Shell](https://github.com/BosEriko/zsh.git) (zsh) - Includes ZSH, Oh My ZSH and Git Configuration
- [Distro](https://github.com/BosEriko/nix.git) (nix) - Includes NixOS Configuration, Flakes, Home Manager, etc.

## Clone the repository
To start you must first clone the repository. Run the command below on NixOS on WSL to clone the repository.
``` sh
git clone --recurse-submodules https://github.com/BosEriko/config.git ~/config
```
