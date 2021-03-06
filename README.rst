neo4j-table-data
================

An application written in python to import structured table data (eg. CSV files) into a neo4j database.

Read more about neo4j here: http://neo4j.org/

Prerequisites
-------------

The neo4j-table-data is a python application, which means that you first have to install python. All programs/packages necessary to install are listed below:

- Python 2.7, see http://www.python.org/
- Python bindings for embedded Neo4j, see https://github.com/neo4j/python-embedded
- CPython with JPype installed http://jpype.sourceforge.net/ (required by python-embedded)

If you are on Mac OS X Lion, follow these instructions to successfully install JPype:
http://stackoverflow.com/questions/8525193/cannot-install-jpype-on-os-x-lion-to-use-with-neo4j


Optional prerequisites
----------------------
If you want to try out your data we recommend to install a neo4j server:
http://docs.neo4j.org/chunked/stable/server-installation.html

As well as their webadmin:
http://docs.neo4j.org/chunked/stable/tools-webadmin.html

Installation from source
------------------------

Download package and unzip.
  
How to use
----------

Make sure you are in the program folder.

::

  python import-nodes.py -i data.csv -o database

