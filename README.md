# BlackArch
Commands Line Interface 


# BLACKARCH BASIC COMMANDS

UPDATE REPOSITORY
sudo pacman --sync --refresh

UPDATE PGP KEYS
sudo pacman --sync --needed -archlinux-keyring

UPDATE SYSTEM 
sudo pacman --sync --sysupgrade
sudo pacman --sync --refresh --sysupgrade 

REBOOT 
reboot

INSTALL
sudo pacman -S --needed git base-devel

YAY
chmod 777 yay
makepkg -si

UPDATE UPGRADE 
sudo pacman -Sy
sudo pacman -Syu
sudo pacman -Syyu
sudo yay -Syu

INSTALLATION
sudo pacman -S cmatrix
sudo pacman -S cmatrix vlc python
yay -S packagename 

INFORMATION
pacman -Qi cmatrix

REMOVING 
sudo pacman -R cmatrix

REMOVE ALL 
yay -R cmatrix
yay -Rns cmatrix
yay -Yc

