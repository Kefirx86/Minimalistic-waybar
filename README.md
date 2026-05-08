# Minimalistic-waybar
a very minimalistic waybar and hyprland config for my laptop, semi inspired by armored core for answer (took the colors from there), technically work in progress but idk if i will ever finish it bcz i have terminal laziness


Put the waybar folder (most of you probably dont need the hyprland config) inside of /home/<insert your user>/.config/

this is a config i have for my laptop so it displays  battery and such aswell
to remove it, go inside the config files and delete unnecessary features

use scripts.sh to refresh waybar so you can see the changes in real time, make sure to make it executable ofc.
example on how to bind it in hyprland:
bind = $mainMod, D, exec, /home/<insert your user>/.config/waybar/scripts.sh

Extra things if something isnt working:

your device might be using the wlo1 interface, if you dont see network being displayed in waybar, that might be due to that, simply go into the waybar/config.jsonc and change it from wlan0 to wlo1.



<img width="4000" height="1848" alt="example" src="https://github.com/user-attachments/assets/efc1cd66-fef1-42ca-8a18-803e0ddce952" />


