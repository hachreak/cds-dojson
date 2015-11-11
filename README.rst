========
 DoJSON
========

.. image:: https://img.shields.io/travis/CERNDocumentServer/cds-dojson.svg
        :target: https://travis-ci.org/CERNDocumentServer/cds-dojson

.. image:: https://img.shields.io/coveralls/CERNDocumentServer/cds-dojson.svg
        :target: https://coveralls.io/r/CERNDocumentServer/cds-dojson

.. image:: https://img.shields.io/github/tag/CERNDocumentServer/cds-dojson.svg
        :target: https://github.com/CERNDocumentServer/cds-dojson/releases

.. image:: https://img.shields.io/pypi/dm/dojson.svg
        :target: https://pypi.python.org/pypi/dojson

.. image:: https://img.shields.io/github/license/CERNDocumentServer/cds-dojson.svg
        :target: https://github.com/CERNDocumentServer/cds-dojson/blob/master/LICENSE


About
=====


Build and Run Docker image
==================

You can run docker build: ::

  docker build -f ./Dockerfile-dev -t cds-dojson .

After the end of the process, you can run: ::

  docker run -it --r `pwd`:/home/cds-dojson/.virtualenvs/cds-dojson/src/code cds-dojson bash


Installation
============


Documentation
=============

Documentation can be built using Sphinx: ::

  pip install cds-dojson[docs]
  python setup.py build_sphinx

Testing
=======

Running the test suite is as simple as: ::

  python setup.py test
