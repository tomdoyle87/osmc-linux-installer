OSMCInstaller compiled with qt5.9.7 staic build, on centos7 with recommded patches from qt5-qtbase-5.9.7-4.el7.src with the following flags:

        -v \
	        -verbose \
		-confirm-license \
		-opensource \
		-prefix ../install \
		-no-qml-debug \
		-no-sql-sqlite \
		-no-sql-db2 \
		-no-sql-ibase \
		-no-sql-mysql \
		-no-sql-oci \
		-no-sql-odbc \
		-no-sql-psql \
		-no-sql-sqlite2 \
		-no-sql-tds \
		-nomake examples \
		-reduce-exports \
		-nomake tests \
		-static \
		-skip wayland \
		-skip qtwebengine \
		-qt-xcb \
		-qt-zlib \
		-qt-pcre \
		-qt-libpng \
		-qt-libjpeg \
		-qt-freetype \
		-make libs \
		-optimized-qmake \
		-no-opengl \
		-skip qtactiveqt \
		-skip qtlocation \
		-skip qtmultimedia \
		-skip qtserialport \
		-skip qtquickcontrols \
		-skip qtscript \
		-skip qtsensors \
		-skip qtwebsockets \
		-skip qtxmlpatterns \
		-skip qt3d \
		-skip qtcharts \
		-skip qtscript \
		-skip qttranslations \
		-skip qtgamepad \
		-skip qtwebchannel \
		-openssl-runtime 

ubuntu22.04 may require libfuse2 to be installed.
