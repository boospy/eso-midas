# eso-midas
[![ESO-MIDAS](http://www.eso.org/i/esologo.png)](https://github.com/boospy/eso-midas)

The ESO-MIDAS system provides general tools for image processing and data
reduction with emphasis on astronomical applications including imaging and
special reduction packages for ESO instrumentation at La Silla and the VLT at
Paranal. In addition it contains applications packages for stellar and
surface photometry, image sharpening and decomposition, statistics and
various others. This package includes the full version with all features and the TSA-Patch.

## Installation of the package also over us signed repository for Ubuntu 16.04 and 18.04.
Repository:
https://apt.iteas.at

WIKI:
https://deepdoc.at/dokuwiki/doku.php?id=rund_um_den_desktop:eso-midas_installation_auf_ubuntu
### Type as root:

	apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 2FAB19E7CCB7F415

	For Ubuntu 18.04
	echo "deb https://apt.iteas.at/iteas bionic main" > /etc/apt/sources.list.d/iteas.list

	For Ubuntu 16.04
	echo "deb https://apt.iteas.at/iteas xenial main" > /etc/apt/sources.list.d/iteas.list
	apt update
	apt install eso-midas-tsa

After installation you have to add your USER to the midas group and relogin, to have
writeaccess to the "baches" folder. (/usr/local/share/midas/VERSION/contrib/baches)
