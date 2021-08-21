# osmc-host-installer
 
osmc-installer_128_amd64.deb - Should work Debian 10/11 and derivatives (Ubuntu, mint, etc)</BR>
osmc-installer-128.x86_64.rpm - Should work on Redhat 8  and derivatives (Fedora, Centos, Rocky, etc) 7 support to be added. 

If for any reason the provided packages do not work for you or you have request for additional distro support, please raise a github issue. Alternativly compile from source:
 
Depends: qt5-devel gcc gcc-c++ make zlib-devel git xhost*

git clone https://github.com/tomdoyle87/osmc-host-installer.git</BR>
cd osmc-host-installer</BR>
qmake</BR>
make</BR>
xhost si:localuser:root && sudo ./qt_host_installer && xhost -si:localuser:root

* Generic package names given
