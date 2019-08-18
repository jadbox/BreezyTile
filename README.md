# BreezyTile
## A tiling shell replacement for GNOME Shell to simplify your workflow and accelerate your productivity.

The project is based upon [Material Shell](https://github.com/PapyElGringo/material-shell). Material-Shell aims to apply a 'material' replacement of gnome's panels, while BreezyTile aims at keeping/focusing on all the fancy tiling management without actually changing gnome's UI. This GNOME Shell extension provides a performant, opinionated mouse/keyboard workflow, but without any changes to the actual gnome shell layout.

## Demo
(outdated demo video)
![Demo GIF](demo.gif)

#
#### STATUS: BETA (expect bugs!)
#### REQUIRES: gnome-shell >=3.32.0

## Installation
1) Clone the project to the gnome-shell extensions folder:
```bash
git clone https://github.com/jadbox/breezytile.git ~/.local/share/gnome-shell/extensions/breezytile@jadbox
```
2) Reload GNOME Shell:
  + On X.org: Hit `Alt+F2` and type the command `r`
  + On Wayland: Log out and back in
3) Open `gnome-tweaks` and activate the `BreezyTile` extension **OR** enable it using 
```bash
gnome-shell-extension-tool -e breezytile@jadbox
```

### Arch Linux
1) You can choose to install using the Arch Linux User-Community Repository (AUR) https://aur.archlinux.org/packages/gnome-shell-extension-breezytile-git/ \
Assuming you're using yay:
```
yay -S gnome-shell-extension-breezytile-git
```
2) Reload GNOME Shell:
  + On X.org: Hit `Alt+F2` and type the command `r`
  + On Wayland: Log out and back in
3) Open `gnome-tweaks` and activate the `BreezyTile` extension **OR** enable it using 
```bash
gnome-shell-extension-tool -e breezytile@jadbox
```

## Workflow Hotkeys
Some hotkeys might already be used by GNOME Shell - please check your keybindings first.
#### Desktop navigation
* `Super+W` Navigate to the upper workspace/category.
* `Super+S` Navigate to the lower workspace/category.
* `Super+A` Focus the window at the left of the current window.
* `Super+D` Focus the window at the right of the current window.

#### Window manipulation
* `Super+Q` Kill the current window focused.
* `Super+[MouseDrag]` Move window around.
* `Super+Shift+A` Move the current window to the left.
* `Super+Shift+D` Move the current window to the right.
* `Super+Shift+W` Move the current window to the upper workspace.
* `Super+Shift+S` Move the current window to the lower workspace.

#### Extra Hotkeys
* `Super+Space` Cycle the tiling layout of the current workspace.
* `Super+Escape` Toggle the UI of BreezyTile, like a Zen mode.

## Optional Configuration
* Get [Plata Theme](https://gitlab.com/tista500/plata-theme) as the GTK and shell theme 
* Get [Tela Icon Theme](https://github.com/vinceliuice/Tela-icon-theme) as the icon theme
