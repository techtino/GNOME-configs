## Gsettings I want

```
gsettings set org.gnome.desktop.wm.keybindings switch-applications "['<Alt>Tab']"
gsettings set org.gnome.desktop.wm.keybindings switch-windows "['<Super>Tab']"
```
These are due to the extension I use for alt-tab mouse focusing only working on switch-windows (this actually is a benefit as sometimes I don't want the mouse to move anyway)

# I want to focus the window that my mouse is currently on
<code>gsettings set org.gnome.desktop.wm.preferences focus-mode 'sloppy'</code>

# Set gtk theme (Saves the time of going into gnome tweaks, run after installing adw-gtk3-git only
<code>gsettings set org.gnome.desktop.interface gtk-theme 'adw-gtk3-dark'</code>
