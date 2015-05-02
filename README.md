# Vertex Icons (Beta)

**Note:** This is an unfinished beta version. It may not work as expected in some cases.

The Vertex icon theme is designed to go well together with the Vertex Gtk theme.
At the moment it includes mainly icons for folders and mimetypes.

### Requirements

Since this theme doesn't provide application icons, it needs another icon theme to inherit them.
By default this theme will look for the Moka icon theme (http://mokaproject.com/moka-icon-theme/) to get the missing icons. If Moka is not installed it will use the Gnome icon theme as fallback.
To change the application icons, edit the `index.theme` file and replace `Moka` with the name of your preferred icon theme

For example, if you like the Faenza icon theme, change

    [Icon Theme]
    Name=Vertex-Icons
    Inherits=Moka,gnome,hicolor
    Comment=Vertex Icon theme

to

    [Icon Theme]
    Name=Vertex-Icons
    Inherits=Faenza,gnome,hicolor
    Comment=Vertex Icon theme

### Installation

Copy the folder which contains this README to `~/.icons` or to `/usr/share/icons` for system-wide use.

### Bug reporting

If you find a bug, please report it at https://github.com/horst3180/Vertex-icons/issues

### Credits

All credits for third party icons used in this theme go to their respective creators:

**elementary:** https://launchpad.net/elementaryicons licensed under the terms of the GPL v3

**elementary-xfce:** https://github.com/shimmerproject/elementary-xfce licensed under the terms of the GPL v2

**Faenza:** https://code.google.com/p/faenza-icon-theme/ licensed under the terms of the GPL v3

**Faience:** https://code.google.com/p/faience-theme/ licensed under the terms of the GPL v3

**GNOME Project:** http://www.gnome.org licensed under the terms of either the GNU LGPL v3 or Creative Commons Attribution-Share Alike 3.0 United States License

**Moka:** http://mokaproject.com/moka-icon-theme licensed under the terms of the GPL v3

The remaining icons are created by Horst3180 and are licensed under the terms of the GPL v3

===

![alt tag](http://i.imgur.com/paECSRR.png)
