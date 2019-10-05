# wayland-scanner-_06.10.2019-1_amd64.deb-source
wayland-scanner++_06.10.2019-1_amd64.deb + source



&& sudo apt purge libwayland-bin wayland-scanner

inpack source code wayland-scanner++.tar.xz

&& make && sudo checkinstall
