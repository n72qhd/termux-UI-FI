This script will install and configure termux-x11 on your device.


REQUIREMENTS:

Android 7 or newer;

Stable internet connection;

Termux (should be already installed on your device);

Installed termux-x11 app;

Atleast 2 gigs of free space;

Installation:

First of all, you'll need to install wget and nano (should be preinstalled by default).

then do nano .termux/termux.properties (from your home folder), and uncomment "allow-external-apps=true".

Then go to your home directory, and type wget https://github.com/n72qhd/termux-UI-FI/blob/main/termux-x11FI.sh
Once it has finished downloading, write chmod +x termux-x11FI.sh

Now you'll have to wait until it installs dependencies and additional packages.

When it's done the script will prompt you to write ./startx.sh to launch XORG. Once you've launched X window system, open termux-x11 and it should connect
to XFCE desktop enviroment. And if it does, congratulations, you've installed termux-x11!

