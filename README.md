# Personalization
Personal configuration files for Windows and Linux environments.

## What's inside

- **PowerShell + Starship** — PowerShell 7 profile and Starship prompt config (Catppuccin Mocha theme)
- **Zsh/Bash** — shell aliases, functions, and `.zshrc` / `.bashrc` dotfiles
- **Kali / WSL** — tweaks and configs for running Kali Linux on WSL2

## Structure

```
dotfiles/
├── powershell/
│   ├── Microsoft.PowerShell_profile.ps1
│   └── starship.toml
├── zsh/
│   ├── .zshrc
│   └── .p10k.zsh
└── wsl
```

## Usage

Clone the repo and symlink or copy the files to their respective locations.

```bash
https://github.com/k1dd03/personalization
```

> Adjust paths as needed depending on your setup.

## Requirements

- [Starship](https://starship.rs/) — cross-shell prompt
- [PowerShell 7](https://github.com/PowerShell/PowerShell) — for Windows configs
- [WSL2](https://learn.microsoft.com/en-us/windows/wsl/) with Kali Linux

## Notes

These are personal configs — feel free to use them as a base, but expect opinionated defaults.
