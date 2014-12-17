i3wm_settings
=============

This is my custom i3wm settings for fast reference and automation. You can freely use and adapt to your environment.

Features
--------
* Removed the title bars from windows decorations
* Konsole for the terminal emulator, as it is really fast and has some cool features I use a lot and I miss in other terminal, features like search at google for the selected words and triple click selection, and other features I don't use so much, but I like to have, like transparency support or random color background/foreground.
* It automatically launches Firefox browser at workspace 1, Thunderbird email client at workspace 2, and Quassel IRC client at workspace 3
* It also launches two applets: kmix and nm-applet, to easily configure sound and network.
* Hotkeys for (l) lock, (e) logout, (s) suspend, (h) hibernate, (r) reboot, (Shift+s) shutdown
* i3bar with status notification, changing the color if any workspace needs your attention.

Installation
------------
Make sure you have installed all dependencies: dmenu, python and compton and simply put all the files on ~/.i3/


Considerations
--------------
Keyboard is in spanish, so you should change the language, set on `config`. Search for `exec setxkbmap es` and change the country code for your own.
