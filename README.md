# My I3 config files
## Using Programms and Fonts
- CMST
- i3lock
- terminator
- feh
- gnome-settings-daemon
- picom (optional)
- mpd (optional)
- ncmpcpp (optional)
- FontAwesome
  
## Autoastart
- cmst
- i3lock
- feh 
- gnome-settings-daemon
- picom (disable - remove the '#' )
  
### Instalation programms and fonts on Archlinux 

> sudo pacman -S --needed cmst i3lock terminator feh gnome-settings-daemon picom mpd ncmpcpp ttf-font-awesome otf-font-awesome powerline

  
<br>
  
# I3 Key Bindings

## Programme
### start a terminal
- _Key: ALT+RETURN_

### Rofi
- _Key: ALT+D_

### I3 dmenu destop
- _Key: ALT+SHIFT+D_

### kill focused window
- _Key: ALT+SUPER+Q_
- _Key: ALT+F4_

## Workspace

### Switch workspace 1-8
- _Key: ALT+{1..8}_

### move focused container to workspace
- _Key: {F1...F8}_


## Layout

### toggle tiling / floating
- _Key: ALT+SUPER+SPACE_

### change focus between tiling / floating windows
- _Key: ALT+SPACE_

### container layout stacked
- _Key: ALT+F9_ 

### container layout tabbed
- _Key: ALT+F10_ 

### container layout split
- _Key: ALT+F11_ 

### split in horizontal orientation
- _Key: ALT+H_ 

### split in vertical orientation
- _Key: ALT+K_ 

### Fullscreen
- _Key: ALT+F12_ 

## Focus 

### focus the parent container
- _Key: ALT+A_

### move focused window, with the cursor keys
- _Key: ALT+SUPER+{LEFT, RIGHT, UP, DOWN}_

### change focused window, with the cursor keys
- _Key: ALT+{LEFT, RIGHT, UP, DOWN}_

## Resize 
### Start Resize mode 
- _Key: ALT+D_


### Shring and Grow 
- _Key: Cursor-Keys_

### End Resize mode
- _Key: ALT+D_
- _Key: ENTER_
- _Key: ESCAPE_

## Utils
### screenshot
- _Key: SUPER+F12_

### Disable / Enable Touchpad
- _Key: SUPER+F11_

### Audio-Volumen Up
- _Key: ALT+P_
- _Key: XF86AudioRaiseVolume_

### Audio-Volumen Down
- _Key: ALT+Y_
- _Key: XF86AudioLowerVolume_

### Audio-Volumen Un-/Mute 
- _Key: XF86AudioMute_

### Hide/unhide i3status bar
- _Key: ALT+M_

### reload the configuration file
- _Key: ALT+SUPER+J_
### restart i3
- _Key: ALT+SUPER+P_

## System 
### Show System Menu
- _Key: ALT+PAUSE_
- After this, press key:
  - 'S' for shutdown.
  - 'R' for restart. 
  - 'L' for logout. 

## Have fun :)