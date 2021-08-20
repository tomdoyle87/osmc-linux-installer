# osmc-host-installer
## qt 5.9.5 static build
sudo apt-get build-dep -y qt5-qmake</BR>
sudo apt-get install  libssl1.0-dev</BR>
sudo apt install python

http://mirrors.ukfast.co.uk/sites/qt.io/archive/qt/5.9/5.9.5/single/qt-everywhere-opensource-src-5.9.5.tar.xz

mkdir build</BR>
cd build</BR>
../configure -opensource -confirm-license -release --prefix=/usr/local -optimized-qmake -no-qml-debug -no-sql-sqlite -no-sql-db2 -no-sql-ibase -no-sql-mysql -no-sql-oci -no-sql-odbc -no-sql-psql -no-sql-sqlite -no-sql-sqlite2 -no-sql-tds -nomake examples -reduce-exports -static</BR>
make -j8</BR>
sudo make install
