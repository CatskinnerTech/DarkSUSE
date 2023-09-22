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
sudo zypper in thunderbird githubdesktop

```
b. Install Fonts
    1. Install MS Compatability Fonts
    ```
    sudo zypper install fetchmsttfonts
    ```
    2. Install Nerdfonts:
    ```
    https://www.nerdfonts.com/font-downloads
    ```
        a. MesloLG
        b. FiraCode
    - Save as .zip files in downloads folder
    - In terminal:
    ```
    cd Downloads/
    unzip Meslo FiraCode
    rm Meslo.zip
    mkdir ~/.fonts
    mv * ~/.fonts
    cd ~/.fonts
    fc-cache -vf

    ```

## Initial Configs
1. Beautful Bash
2. Neovim


##
