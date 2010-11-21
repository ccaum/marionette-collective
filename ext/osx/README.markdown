OS X Tools
==========

This contains a script to build mcollective packages for Mac OS X.  

bldmacpkg
---------

This script will automatically build Mac packages based on your source
tarball. It automatically determines the MCollective version so it will only work
with 0.4.9 and forward.  It loads mcollective in ruby so it requires
that the stomp rubygem be installed.


### Requirements

* XCode Tools installed

* Unpacked mcollective source tarball >= 0.4.9

* stomp ruby gem installed

### Parameters

* The first parameter must be the path to the unpacked mcollective source tarball

### Contact

Carl Caum - carl _at_ carlcaum.com
