Dirbypy
--------

.. image:: https://img.shields.io/pypi/v/Dirbypy.svg
    :target: https://pypi.org/project/Dirbypy/
.. image:: https://img.shields.io/pypi/pyversions/Dirbypy.svg
    :target: https://pypi.org/project/Dirbypy/
.. image:: https://travis-ci.org/marcolivierbouch/Dirbypy.svg?branch=master
    :target: https://travis-ci.org/marcolivierbouch/Dirbypy

Description
-----------
Dirbypy - URL Bruteforcer

This is a new version of dirb but in python. This version is faster than the normal version in C because it uses thread. Dirbypy is a Web Content Scanner. It looks for hidden Web Objects. It basically works by launching an attack based on a dictionary against a web server and analyzing the response.

Link to the original dirb: https://github.com/v0re/dirb

Install with pip
----------------
``pip install Dirbypy``

Fish completions
----------------
``git clone https://github.com/marcolivierbouch/Dirbypy.git``

``cd Dirbypy``

``sudo cp Dirbypy.fish /usr/share/fish/completions``

Dirbypy with Docker
------------------
Pull the Docker

``docker pull marcolivierbouch/Dirbypy``

After you need to get inside the docker

``docker run -it marcolivierbouch/Dirbypy``

Command example

``Dirbypy -o https://raw.githubusercontent.com/danielmiessler/SecLists/master/Discovery/Web-Content/common.txt -u https://[....].com``

Recommendations
---------------
I recommend using the SecLists: https://github.com/danielmiessler/SecLists
