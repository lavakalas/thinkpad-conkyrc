## Wayland port

Require [Conky](https://github.com/brndnmtthws/conky) is installed in your system and built with BUILD_WAYLAND flag. (Yes, you'll have to build it yourself)

Tested with Hyprland and Hyprpaper

# Install

```
$ mkdir -p ~/.conky/Thinkpad && git clone https://github.com/lbngoc/conkyrc.git ~/.conky/Thinkpad
$ sed -i -e "s/ngoclb/$(whoami)/g" ~/.conky/Thinkpad/thinkpad-t440.conkyrc
```

Setup `thinkpad-wallpaper.png` as your desktop wallpaper.



# Usage

```
$ conky -q -c ~/.conky/Thinkpad/thinkpad-t440.conkyrc &> /dev/null
```

# Screenshot

- Thinkpad
![](screen.png)
