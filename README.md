this is my dotfiles repo, managed with stow, tutorial may be incomplete, should be fully updated before reinstall (if needed)
# tutorial
# first, install git
 sudo pacman -S git

# install stow 
 sudo pacman -S stow

# install cachyos repo onto arch 
https://wiki.cachyos.org/features/optimized_repos/

# install necessary packages from pacman 
 sudo pacman -S hyprland hyprshot hyprpicker hyprpaper hyprsunset fastfetch neovim btop rofi-wayland yazi cava kitty nwg-look fish

# install yay
https://youtu.be/NzNuFN9hqjI?si=ViNSwoosGHvR-2yF

# install needed packages from yay
 yay -S waypaper matugen-git millennium vesktop ags-hyprpanel-git swww-git

# clone this github repo
git clone git@github.com:bluecxmboo/dotfiles.github

# run stow 
stow . (if that fails, cd into directory and manually stow each folder)


