# Development Environment Setup
Archive of personal development environment autosetup for Unix-like systems.

# Autosetup

## System requirements
The following tools are required to be installed on your system:
- git
- curl 
- zsh
- python3

The following tools are optional but recommended:
- tmux

## How to use
To run the autosetup script, run the following command in your terminal.
IMPORTANT: You must run this code using python3. Dosen't matter version of the python3.

```bash
python3 -c "$(curl -fsSL https://raw.githubusercontent.com/Fitree/DevEnvSetup/refs/heads/main/scripts/autosetup.py)"
```

This will setup
- zsh + oh-my-zsh + p10k terminal environment with useful plugins
- Setup useful config files: `.zshrc`, `.p10k.zsh`, `.tmux.conf`
  - Existing config files will be backuped to the `~/config_backup`
- Install claude code

# Development Container
You can use the development container to run the autosetup script.
