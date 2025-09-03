this is my dotfiles repo, managed with stow, tutorial may be incomplete, should be fully updated before reinstall (if needed)
# tutorial
# first, install git
 sudo pacman -S git

# install stow 
 sudo pacman -S stow

# install cachyos repo onto arch 
https://wiki.cachyos.org/features/optimized_repos/

# install necessary packages from pacman 
 sudo pacman -S hyprland hyprshot hyprpicker hyprpaper hyprsunset fastfetch neovim btop rofi-wayland yazi cava kitty nwg-look fish gtk4 gtk3 python-pywal python-watchdog

# install yay
https://youtu.be/NzNuFN9hqjI?si=ViNSwoosGHvR-2yF

# install needed packages from yay
 yay -S waypaper matugen-git millennium vesktop ags-hyprpanel-git swww-git rofi-power-menu 
# allow flatpak apps to access gtk theme
sudo flatpak override --filesystem=xdg-config/gtk-3.0 && sudo flatpak override --filesystem=xdg-config/gtk-4.0

# install nvchad
https://nvchad.com/docs/quickstart/install/

# install pywal theme for nvchad
https://github.com/NvChad/pywal

# clone this github repo
git clone git@github.com:bluecxmboo/dotfiles.github

# run pywal first to generate neovim theme
wal -i (any wallpaper)

# run stow 
stow btop fastfetch fish hypr hyprpanel kitty matugen nvim rofi vimrc walset-backend yazi wallpapers pywal gtk3 gtk4 
