geoserver-deb
=============

Debian package for geoserver


Instructions
------------

Before using it, unpack a geoserver war into the following folder: 

```
usr/share/geoserver/geoserver-X.X
```

and make the following symlink point to it:

```
usr/share/geoserver/geoserver-X.X
```

To build the package do:

```
dpkg --build geoserver-deb ./
```
