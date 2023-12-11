# DarkSUSE
My semi-minimal OpenSUSE Tumbleweed setup using the AwesomeWM and XORG
Auto installs all my desired packages for a main desktop machine, 
and includes config files for themeing the desktop and main apps.

# IS NOT CURRENTLY READY

## Install Instructions
1.  Boot OpenSUSE TW install media
2.  Select Server Install
3.  Under Software Selection
    -   Select Details > Prefrences > Required Only (Deselect "Recommended")
    -   Select KVM/QEMU
    -   Set all 5 YAST patterns to Taboo
4.  Under Network
    -   Set Hostname to desired (can be done later)
5.  Install & Reboot
6.  Login and Update System
```
```

7.  Install git and Curl
```
sudo zypper in git and curl
```
8.  Download and activate DarkSuSE Script:
```
mkdir ~/GitHub/dotfiles
cd ~/GitHub/dotfiles
git clone https://github.com/CatskinnerTech/DarkSUSE
cd DarkSUSE
exec darkSUSE.sh
```

## Packages and Configs Included
Below is a list of all packages included in the install script
and which have custom themes or config files.

0.  Excludes all YAST & Uses Required Only
1.  Includes the following packages:
    1.  XORG
    2.  LightDM
    3.  Awesome
    4.  XORG
    5.  Pipewire...?
    6.  Alacritty
    7.  Neovim
    8.  Thunar
    9.  Rofi
    10. Brave-Browser
    11. Librewolf/Mullvad
    12.   

2.  Includes config or theme files for the following:
    1.  LightDM
    2.  Awesome
    3.  Alacritty
    4.  Neovim
    5.  Rofi
    6.  Browser Themes
        -   Brave
        -   Librewolf/Mullvad
    7.  Fastfetch
    8.  Thunderbird
    9.  Office - MS Office Compatibility
