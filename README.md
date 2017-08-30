## PySQLPool for Python3 ##

What is PySQLPool
=================

PySQLPool is at the heart a MySQL Connection Pooling library for use with the MySQLDB Python bindings.

Part of the PySQLPool is the MySQL Query class that handles all the thread safe connection locking, 
connection management in association with the Connection Manager, and cursor management. 
Leaving all the work you have to do in your code is write MySQL Queries. Saving you hours of work.

Installation
============

Linux/Mac OS X:
cd PySQLPool
python setup.py build
sudo python setup.py install

Windows:
cd PySQLPool
python setup.py build 
python setup.py install 

How to Use PySQLPool
====================

Documentation can be read locally at doc/index.rst or via the web at http://packages.python.org/PySQLPool

You can also generate your own html docs via the make file in doc/. This will produce the same docs as 
hosted on the website.

PySQLPool License
=================

PySQLPool is licensed under the LGPL. You can find out more in the included LICENSE file.

Documentation: http://packages.python.org/PySQLPool/
