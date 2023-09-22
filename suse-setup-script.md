# OpenSUSE TumbleWeed Config Notes and Script

## Initial Software Set-up Selections
1. Software - Block wayland (taboo) in details for KDE
2. Add Brave and Pacman Repos
```
Addrepo...
```
3. Libreoffice

6. Remove Firefox
7. Remove Discover
8. Remove KDE wallet (Not manager unless you have the wallet removed!)
9. Other Stuff


## Inital Installs
```
sudo zypper in neovim curl go hugo python brave-browser
sudo zypper in thunderbird

```
b. Install Fonts
```
zypper addrepo https://download.opensuse.org/repositories/openSUSE:Factory/standard/openSUSE:Factory.repo
zypper refresh
zypper install fetchmsttfonts
```
    Install Nerdfonts:
    ```
    https://www.nerdfonts.com/font-downloads
    ```
        1. MesloLG
        2. FiraCode
    - Save as .zip files in downloads folder
    - In terminal:
    ```
    cd Downloads/
    unzip Meslo
    rm Meslo.zip
    mkdir ~/.fonts
    mv * ~/.fonts
    cd ~/.fonts
    fc-cache -vf
    
    ```
    ```    
    unzip FiraCode
    ```

## Initial Configs
1. Beautful Bash
2. Neovim


##
