<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/repo-banners/cybr-fastfetch-banner.png" height=200px/>

# Showcase
<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/showcase/cybr-fastfetch.png"/>

# Steps
## 0. Before you start
- Make sure [Geist Mono Nerd Font](../INSTALL.md#prerequisites--setup#Fonts) is installed, you can do that from terminal with:
```bash
curl -L https://github.com/ryanoasis/nerd-fonts/releases/latest/download/GeistMono.zip -o GeistMono.zip
mkdir -p ~/.local/share/fonts
unzip GeistMono.zip -d ~/.local/share/fonts/GeistMono
fc-cache -fv
```
- Make sure kitty is installed: `sudo pacman -S kitty` and [cybrcore theme](https://github.com/cybrcore/cybr-kitty) is applied
- Make sure broot is installed: `sudo pacman -S broot` and [cybrcore theme](https://github.com/cybrcore/cybr-fish) is applied
- See [Installation Guide](https://github.com/cybrcore/cybrland/blob/main/INSTALL.md) if you`re coming from [cybr-hyprland](https://github.com/cybrcore/cybrland) and haven't set up prerequisites yet
- [fastfetch Github repo](https://github.com/fastfetch-cli/fastfetch)

## 1. Create theme folder and file
```sh
mkdir -p ~/.config/fastfetch/
$EDITOR ~/.config/fastfetch/config.jsonc
```
## 2. Insert [cybrcore theme](config.jsonc)
## 3. Use
```sh
fastfetch
```
