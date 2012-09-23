plymouth-theme-asphyxia
=======================

Credit for the background image goes to [starweaver](http://starweaver.deviantart.com)

## Install

### Archlinux
A package is available in the user repositories

### Others

Depending of your linux disribution, some paths may need to be changed :

* First locate your plymouth configuration directory (usualy */usr/share/plymouth* or */lib/plymouth*).
* Then, if the path is **NOT** */usr/share/plymouth* you will have to open *asphyxia.plymouth* and replace */usr/share/plymouth* by the correct path.

Now, open a terminal :

    git clone git://github.com/Nivl/plymouth-theme-asphyxia.git
    cd plymouth-theme-asphyxia
    # Edit asphyxia/asphyxia.plymouth if needed.
    # In the next commande replace [YOUR_PATH] by the correct one (the brackets need to be replaced too)
    cp -r asphyxia [YOUR_PATH]/themes/

    plymouth-set-default-theme -R asphyxia

That's all!
