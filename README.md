# Config
This is my personal config for Windows 11. Feel free to use it or fork it.

## Installation Scripts
The config is divided into parts for modularity:
1. [Package Manager](https://github.com/BosEriko/scoop.git) (scoop) - Includes Scoop
2. [Hotkeys](https://github.com/BosEriko/powertoys.git) (powertoys) - Includes PowerToys
3. [Window Manager](https://github.com/BosEriko/glaze.git) (glaze) - Includes GlazeWM
4. [Editor & Terminal](https://github.com/BosEriko/vs.git) (vs) - Includes Visual Studio Code
5. [Virtual Machine](https://github.com/BosEriko/wsl.git) (wsl) - Includes WSL
6. [Distro](https://github.com/BosEriko/nix.git) (nix) - Includes NixOS Configuration, Flakes, Home Manager, etc.
7. [Shell](https://github.com/BosEriko/fish.git) (fish) - Includes fish and Git Configuration

_Note: Installation can be done in no order but ideally in order is better._

## Clone the repository
To start you must first clone the repository. Run the command below on NixOS on WSL to clone the repository.
``` sh
git clone --recurse-submodules https://github.com/BosEriko/config.git ~/config
```