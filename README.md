# bspwm
My personal bspwm setup

# BSPWM Dotfiles 
These are my personal bspwm configurations (for Arch btw).
Pics
## Installation
Yay installation (an aur helper)
```
sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
```
Install packages
```
yay -S bspwm-rounded-corners alacritty firefox picom neofetch lxappearance thunar thunar-archive-plugin thunar-media-tags-plugin thunar-volman ranger nano mpv polybar sublime-text-4 fish polkit-gnome pavucontrol firefox dunst arandr picom kitty redshift neofetch git rofi tar unzip nitrogen zathura archlinux-wallpaper feh gcolor3 nerd-fonts-complete ttf-ms-fonts urxvt-perls urxvt-resize-font-git urxvtconfig-git tela-icon-theme-git lightdm lightdm-webkit2-greeter lightdm-webkit2-theme-reactive flat-remix-gtk rofi-greenclip rofi-power-menu pamixer ntfs-3g python-pip tk 
(xone steam davinci-resolve vlc goimp inkscape discord visual-studio-code gparted iriun yad)
```
Change shell to fish
```
chsh -s /usr/bin/fish
