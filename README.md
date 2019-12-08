# AIMPAC2-Suite
Current release: *'Fresnel'*

A suite of software built around AIMPAC2.

First release to progress in phases: currently, AIMPAC2-Suite tools are being uploaded 
progressively to subdirectory 'tools'.

Most AIMPAC2-Suite tools are implemented in Python 3 and are released as 'pip'-installable source distribution archives, following a calendar versioning scheme. Most of these Python-based tools also depend on the modules 'beacon_utils' and 'molgraph', so these must be installed prior to the tools themselves.

The intended installation procedure is (using 'pip3' as a synonym for 'pip'):

pip3 install beacon_utils-YYYYMMDD.N.tar.gz

pip3 install molgraph-YYYYMMDD.N.tar.gz

then

pip3 install toolname-YYYYMMDD.N.tar.gz
