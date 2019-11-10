# Ubuntu18.04 主题更换为 Mac OS high Sierra



```
#!/bin/bash

set -ex

sudo apt-get install -y git gnome-tweaks gnome-shell-extensions gnome-shell-extension-dash-to-panel
git clone https://github.com/yifengyou/Ubuntu18.04-MacOS-themes
tar -xvf ./Ubuntu18.04-MacOS-themes/themes/Sierra-light-solid.tar.xz -C /usr/share/themes/
tar -xvf ./Ubuntu18.04-MacOS-themes/icons/MacOSX-cursors.tar.xz -C /usr/share/icons/
tar -xvf ./Ubuntu18.04-MacOS-themes/icons/MacOSX-icon-theme.tar.xz -C /usr/share/icons/
tar -xvf ./Ubuntu18.04-MacOS-themes/backgrounds/HighSierra-wallpapers.tar.xz -C /usr/share/backgrounds/
tar -xvf ./Ubuntu18.04-MacOS-themes/fonts/Fonts-MyraidSetPro.tar.xz -C /usr/share/fonts/
```


