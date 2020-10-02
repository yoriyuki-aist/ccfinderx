ccfinderx
=========

Dependencies:
autotools, build-essential, 
libboost-all-dev,
openjdk-7-dev, ant, 
libicu4j-java, libswt-gtk-java, libtrove-java, libswt-cairo-gtk-3-jni
and others(?)

To compile the project:
1) aclocal
2) automake
3) autoconf
4) cd build
5) PYTHON=python2 ../configure
6) make

GUI does not work.  Use CLI
cd build
./ccfx -h
for usages