# Ubuntu18.04 主题更换为 Mac OS high Sierra



```
#!/bin/bash

set -ex
PWD=`pwd`

sudo apt-get install -y gnome-tweaks gnome-shell-extensions gnome-shell-extension-dash-to-panel
git clone https://github.com/yifengyou/Ubuntu18.04-MacOS-themes
tar -xvf ./Ubuntu18.04-MacOS-themes/themes/Sierra-light-solid.tar.xz -C /usr/share/themes/
tar -xvf ./Ubuntu18.04-MacOS-themes/icons/MacOSX-cursors.tar.xz -C /usr/share/icons/
tar -xvf ./Ubuntu18.04-MacOS-themes/icons/MacOSX-icon-theme.tar.xz -C /usr/share/icons/
tar -xvf ./Ubuntu18.04-MacOS-themesbackgrounds/HighSierra-wallpapers.tar.xz -C /usr/share/backgrounds/
```


