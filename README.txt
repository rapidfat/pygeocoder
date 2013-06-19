==================
pygeocoder 1.2.0.1
==================
Xiao Yu
Sébastien Fievet
Marius Grigaitis
19/03/2010

*Based on googlemaps 1.0.2 by John Kleint*

README
------
This is a Python wrapper for Google Geocoding API V3

It allows you to directly convert an address to coordinates or vice versa. It also allows you to validate, format and split addresses into civic number, street name, city etc.

License
------
BSD

Dependencies
------------
It has dependency on the json module, included with Python versions 2.6 and
later and available for download as simplejson for earlier versions.
functools is needed and included in Python 2.5.
It is developed on Python 2.7 but should work on earlier versions. It is also compatible with Python 3.


Installation
------------
You can install this package using pip:

	sudo pip install pygeocoder

or download the source from http://code.xster.net/pygeocoder and install

	python setup.py install

Usage
-----
Please refer to http://code.xster.net/pygeocoder/wiki for help with usage


Contact Information
-------------------
Author: Xiao Yu
Internet: http://code.xster.net/pygeocoder

For comments, issues, requests, please contact via BitBucket at the above website


Changelog
---------
Version 1.2.0.1
setup.py dependency fix

Version 1.2
Refactor and unit testing
Changed license to BSD
Python 3 compatibility
Business API account support

Version 1.1.4
Fixed UTF-8 and facilitated command line usage

Version 1.1.3
Made Geocoder methods static method while backward compatible

Version 1.1.2
Added address validation

Version 1.1.1
Returns GeocoderResult by default.
Result set accessible by iterator or index.

Version 1.1
Added GeocoderResult in order to ease field retrieval/result parsing.

Version 1.0
Working version an API V3.
