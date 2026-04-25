# Mochajuice

A Catppuccin Mocha-based theme for [Omarchy](https://omarchy.org/), shipped with a tmux-style pill Waybar layout.

## Preview

![Preview](preview.png)

## Install

```bash
omarchy-theme-install https://github.com/rutger1140/omarchy-mochajuice-theme
```

This clones the theme into `~/.config/omarchy/themes/mochajuice` and activates it.

## Optional: pill-style Waybar

The `waybar-theme/` directory contains an opinionated Waybar layout — three colored "pills" (left/center/right) on a transparent bar, dark text on accent backgrounds. Apply it with:

```bash
cp ~/.config/omarchy/themes/mochajuice/waybar-theme/* ~/.config/waybar/
omarchy-restart-waybar
```

To revert to the stock Omarchy Waybar:

```bash
omarchy-refresh-waybar
```

## What's included

- `colors.toml` — palette (Catppuccin Mocha)
- `backgrounds/` — wallpapers
- `btop.theme`, `icons.theme`, `neovim.lua`, `vscode.json`, `waybar.css` — per-app theming
- `waybar-theme/` — optional pill-style Waybar config

## Credit

Color palette: [Catppuccin Mocha](https://github.com/catppuccin/catppuccin).
