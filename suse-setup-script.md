# OpenSUSE TumbleWeed Config Notes and Script

## Initial Software Set-up Selections
1. Software - Block wayland (taboo) in details for KDE
2. Add Brave and Pacman Repos
```
sudo rpm --import https://brave-browser-rpm-release.s3.brave.com/brave-core.asc

sudo zypper addrepo https://brave-browser-rpm-release.s3.brave.com/brave-browser.repo
```
3. Libreoffice
4. Add Thunderbird?
5. 
6. Remove Firefox
7. Remove Discover
8. Remove KDE wallet (Not manager unless you have the wallet removed!)
9. Other Stuff


## Inital Installs
1. Install languages and base programs
```
sudo zypper in neovim curl go hugo python brave-browser
sudo zypper in thunderbird githubdesktop

```
2. Install Fonts
    1. Install MS Compatability Fonts
    ```
    sudo zypper install fetchmsttfonts
    ```
    2. Install Nerdfonts:
    ```
    https://www.nerdfonts.com/font-downloads
    ```
        1. MesloLG
        2. FiraCode
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
