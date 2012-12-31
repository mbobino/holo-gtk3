Info:
=====
* GTK2 based on [Holo by Tiheum](http://tiheum.deviantart.com/art/Holo-280076980)
* GTK3 based on [Holo 3 by r3gis3r](https://github.com/r3gis3r/Holo-Gnome3-Theme)
* Cinnamon based on 
* Only tested on [Ubuntu 12.04 LTS](http://releases.ubuntu.com/precise/) with [Cinnamon Desktop](http://cinnamon.linuxmint.com)

Installation:
=============
To install it directly using command line :

    # Install git (if not already)
    sudo apt-get install git

    # Create .themes folder (if not already)
    mkdir ~/.themes

    # Checkout git repo
    cd ~/.themes && git clone git://github.com/mbobino/holo-gtk3.git

    # Optionally link root theme folder to your folder
    sudo ln -s ~/.themes ~root/.themes

Fonts:
======
To install Roboto fonts:

    # Get roboto fonts
    wget http://www.fontsquirrel.com/fonts/download/roboto -O roboto.zip

    # Create .fonts theme (if not already)
    mkdir ~/.fonts

    # Unzip fonts in folder
    unzip roboto.zip -d ~/.fonts

To Do:
======
* Fix misc issues in themes.
* Add Google Chrome theme that matches.

* Basically I'd like to theme an Ubuntu install to mimic the android frameworks.

Legal:
======
Holo is released under GPLv3.
AOSP artwork is released under Apache license.
So long as you follow the rules in these licenses you can pretty much do what you want with these files. If you have changes that you'd like me to add feel free to send me a pull request and I'll see about adding them.
