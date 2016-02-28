Quake 3 railgun style theme for SDDM
------------------------------------

Based on official SDM theme "maldives".

![Alt Screenshot](https://raw.githubusercontent.com/zolech/railgun-sddm-theme/master/railgun/screenshot.png "Quake 3 railgun style theme for SDDM")

Installation
------------------------------------

Gentoo:

 * layman -o https://raw.githubusercontent.com/zolech/gentoo-ebuilds/master/repositories.xml -f -a xsi
 * emerge -av railgun-artwork-sddm
 * Change current theme variable to "railgun" (Current=railgun) in /etc/sddm.conf
 * Restart X

Sabayon:

 * Download latest binary package from https://github.com/zolech/railgun-sddm-theme/releases
 * equo install <packagename>.tbz2
 * Change current theme variable to "railgun" (Current=railgun) in /etc/sddm.conf
 * Restart X

Manual Installation
------------------------------------
* Copy "railgun" folder to /usr/share/sddm/themes/ location
* Change current theme variable to "railgun" (Current=railgun) in /etc/sddm.conf
* Restart X

Images
------------------------------------
* Background by Igless - http://lgless.deviantart.com/art/Railgun-Wallpaper-328545308
