
## Repo for my attempts on Hyprland 
### Base system will be arch and all DOT files for a RICE will be stored here 

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/CipherCryptic/Linus/blob/main/img/warframe_steam.png">
  <source media="(prefers-color-scheme: light)" srcset="[https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png](https://github.com/CipherCryptic/Linus/blob/main/img/warframe_steam.png)">
  <img alt="My Arch distro on BSPWM currently" src="[https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png](https://github.com/CipherCryptic/Linus/blob/main/img/warframe_steam.png)">
</picture>


***
'Install'       'Theming'      'Features'

***

## List of Linux program, requirements and its requirements 

+ `Arch Vanilla install` (Obviously)
+ `hyprland` (base)
+ `xdg-desktop-portal-hyprland` 
+ `waybar` (top bar)
+ `hyprcursor` (Themes need to obtain those yourself. If you are on the Discord server, see #hyprcursor-themes.)
+ `hyprlock`
+ `hyprpolkitagent` (polkit authentication daemon)
+ `wofi` (Wofi is a GTK-based customizable App launcher for Wayland)
+ `sddm` (Works flawlessly. Install sddm ⩾ 0.20.0)
+ `pipewire` and `wireplumber`
+ `qt5-wayland` and `qt6-wayland` (For Qt support)
+ `epiphany` (Gnome Web browser)
+ `thunar` (File manager)
+ `nemo` (File manager)
+ `dolphin` (File manager)
+ `fish` (shell)
+ `kity` (Terminal
+  or `ZSH` - change shell to zsh (chsh -s $(which zsh)  )
+  `dunst`
+ `neovim`
+ Arch Linux Tweak Tool
+ `quickshell` (yay quickshell) - See the website https://quickshell.outfoxxed.me/ for more information and installation instructions.
+ or `eww`
+ `fastfetch`

## Dependencies (As per Wiki)

`yay -S ninja gcc cmake meson libxcb xcb-proto xcb-util xcb-util-keysyms libxfixes libx11 libxcomposite libxrender libxcursor pixman wayland-protocols cairo pango libxkbcommon xcb-util-wm xorg-xwayland libinput libliftoff libdisplay-info cpio tomlplusplus hyprlang-git hyprcursor-git hyprwayland-scanner-git xcb-util-errors hyprutils-git glaze hyprgraphics-git aquamarine-git re2 hyprland-qtutils`

+ `aquamarine` (a very light linux rendering backend library)
+ `hyprlang` (library that implements parsing for the hypr configuration language)
+ `hyprutils` (library providing shared implementations )
+ `hyprgraphics` (library providing shared implementations of some utilities)




## Nice to have Linux programs

+ Chromium (No  longer like Firefox TBH)
+ Discord 
+ Twitch (Watch the best Linux channels and streamers that are live on Twitch!)
+ Steam   
+ Glava (OpenGL audio spectrum visualizer)
+ YouTube Music 



# Hyprland


## Must have 

>notification daemon 
Examples: `dunst`, `mako`, `fnott and swaync`.

>Pipewire 
Install `pipewire` and `wireplumber` (not pipewire-media-session).

>XDG Desktop Portal
https://wiki.hypr.land/Hypr-Ecosystem/xdg-desktop-portal-hyprland
`xdg-desktop-portal-hyprland`

>Authentication Agent
https://wiki.hypr.land/Hypr-Ecosystem/hyprpolkitagent
`hyprpolkitagent` is a polkit authentication daemon. It is required for GUI applications to be able to request elevated privileges.

>Qt Wayland Support
Install `qt5-wayland` and `qt6-wayland`.
