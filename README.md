# Alex's Arch Linux Dotfiles

A Material Design inspired Hyprland setup using Matugen for dynamic colors.

## 🛠 Features
* **WM:** Hyprland
* **Bar:** Waybar (with dynamic Matugen colors)
* **Colors:** Matugen (Material You)
* **Terminal:** Kitty
* **Wallpaper:** swww

## 📦 Dependencies
Install these to make everything work:
```bash
sudo pacman -S hyprland waybar kitty rofi swww stow nm-applet libappindicator-gtk3
# Install matugen-bin from AUR
yay -S matugen-bin
```

## 🚀 How to Install
1. Clone the repo: `git clone https://github.com/4vertka/hyprland-dot-files.git ~/dotfiles`
2. Link the configs:
```bash
cd ~/dotfiles
stow -vt ~ .config
stow -vt ~ .local
```
3. Set your first wallpaper: `themeChanger /path/to/image.png`
