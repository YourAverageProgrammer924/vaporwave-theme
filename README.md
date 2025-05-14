# vaporwave-theme
A vaporwave theme for Ubuntu (GNOME)

## Screenshots
![Bildschirmfoto vom 2025-05-11 15-21-53](https://github.com/user-attachments/assets/bb870047-596b-4111-bdb9-28002882ac50)


![Bildschirmfoto vom 2025-05-11 15-22-13](https://github.com/user-attachments/assets/7bb3fc7e-6239-40e8-87f7-44e9da299590)


![Bildschirmfoto vom 2025-05-11 15-40-25](https://github.com/user-attachments/assets/98143a48-8333-40a0-bd6b-3fac39e09b43)



![Bildschirmfoto vom 2025-05-11 15-21-36](https://github.com/user-attachments/assets/257f6d86-9a53-4e06-8efc-f9d5e2d1605a)


## General Requirements for this Theme:


- GNOME-Tweaks
- GNOME-Shell-Extensions
- libre-menu-editor 
- kitty terminal
- fastfetch
- oh my zsh
- the wallpaper can be found here: 
  https://en.idei.club/uploads/posts/2023-06/1686655783_en-idei-club-p-purple-grunge-dizain-instagram-8.png


## The following GNOME extensions

- Blur my Shell
- Compiz windows effect
- Desktop Logo
- Favorites to Application Grid
- Just Perfection

# Installation process:


## Clone the repo:


`git clone https://github.com/YourAverageProgrammer924/vaporwave-theme.git`


## Update and Upgrade your System first


`sudo apt update && sudo apt upgrade -y`


## Install all the listed requirements


```
   sudo apt install gnome-tweaks kitty fastfetch -y
   sudo flatpak install flathub com.mattjakeman.ExtensionManager
   sudo flatpak install flathub page.codeberg.libre_menu_editor.LibreMenuEditor
```


## install oh-my-zsh


`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`



## Deinstall the preinstalled GNOME-terminal


`sudo apt remove gnome-terminal -y`


## Make fastfetch + icon appear on terminal startup


### Modify your `~/.zshrc` file


`nano ~/.zshrc`


Now go to the end of the file and add `fastfetch --logo ~/vaporwave_icon_pack/vpn --logo-width 40`


Optional also


`alias vaporfetch="fastfetch --logo ~/vaporwave_icon_pack/vpn --logo-width 40"`


Press `Ctrl+X` to close the file then press `Y` to save the file.


## Icon change


Essentially you open up libre-menu-editor and choose the application, you want to change the icon for.
After that you can click on the symbol tab/the symbol change icon and use my icons (if you want).


![grafik](https://github.com/user-attachments/assets/ca52820a-4291-4af9-9a62-359174b9dd69)




