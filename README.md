# osmc-host-installer
 
osmc-installer_128_amd64.deb - Should work Debian 10/11 and derivatives (Ubuntu, mint, etc)
osmc-installer-128.x86_64.rpm - Should work on Redhat 8  and derivatives (Fedora, Centos, Rocky, etc) 7 support to be added. 

If for any reason the provided packages do not work for you or you have request for additional distro support, please raise a github issue. Alternativly compile from souce:
 
 sudo apt-get install qt5-default qt5-qmake
 git clone https://github.com/tomdoyle87/osmc-host-installer.git
 cd osmc-host-installer
 qmake
 make
 sudo make install
 
 Uninstall:
 
 sudo make Uninstall
