# Combine Mono + Kora Icons for Gnome

This is a mix of Mono symbolic icons and Kora symbolic icons that i made.  I combined Mono Icons with app icons of Kora icons. And remove default folder icons of Mono Icons with Kora Icons. This help icons match and don't get out from the style of Kora icons when you only move the icons from Kora icon pack to `scalable/apps`. Hope you enjoy it!

## Mono Icons
You can see Mono Icons repository [here.](https://github.com/witalihirsch/Mono-icon-theme)

![image](https://github.com/zhaospei/Mono-Kora-icon-theme/assets/48708971/9566067e-af8f-4a72-80a6-37cd34cae6f9)

## Kora Icons
You can see Mono Icons repository [here.](https://github.com/bikass/kora)

![image](https://github.com/zhaospei/Mono-Kora-icon-theme/assets/48708971/b371935c-4c9a-4d2f-93b7-1dd85d2aeabc)


## Download
Download icons [here.](https://github.com/zhaospei/Mono-Kora-icon-theme/releases)

## Installing
To install icons, place the folder in the `~/.icons` directory and select icons in [Gnome Tweaks](https://gitlab.gnome.org/GNOME/gnome-tweaks). In order for icons to work everywhere, including for flatpak apps, go to the directory where you saved the folder and move the icons folder to `/usr/share/icons`.  
Command:  
```pwsh
sudo cp -r MonoKoraIcons /usr/share/icons
```  
## Uninstalling
To remove icons, delete the icons folder in `~/.icons` and select the other icons in Gnome Tweaks. Go to `/usr/share/icons` and open a terminal.  
Command:  
```pwsh
sudo rm -r MonoKoraIcons
```
