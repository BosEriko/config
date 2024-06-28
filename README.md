# Config
This is my personal config for Windows 11. Feel free to use it or fork it.

## Installation Scripts
The config is divided into parts for modularity:
1. [Package Manager](https://github.com/BosEriko/scoop) (scoop) - Includes Scoop
2. [Hotkeys](https://github.com/BosEriko/powertoys) (powertoys) - Includes PowerToys
3. [Window Manager](https://github.com/BosEriko/glaze) (glaze) - Includes GlazeWM
4. [Editor & Terminal](https://github.com/BosEriko/vs) (vs) - Includes Visual Studio Code
5. [Virtual Machine](https://github.com/BosEriko/wsl) (wsl) - Includes WSL
6. [Distro](https://github.com/BosEriko/debian) (debian) - Includes Debian Configuration
7. [Shell](https://github.com/BosEriko/zsh) (zsh) - Includes Zsh, Oh My Zsh and Git Configuration

_Note: Installation can be done in no order but ideally in order is better._

## Clone the repository
To start you must first clone the repository. Run the command below on Debian on WSL to clone the repository.
``` sh
git clone --recurse-submodules https://github.com/BosEriko/config.git ~/config
```