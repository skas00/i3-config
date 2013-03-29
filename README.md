i3 window manager and system configuration files:
=================================================

i3.conf
-------
This is the i3 configuration file that determines the behavior of the window manager. Typical location will be ~/.i3/config

xinitrc.conf
------------
This is a script that executes once X starts. This is where you will start executables. You use this to call .Xresouces, set the wallpaper, and start the window manager. Typical location for the user will be ~/.xinitrc

xresources.conf
---------------
To specify font, font color, and foreground / background colors, we call Xresources. Because you call this file manually, it can be stored anywhere. My location is ~/.Xresources
