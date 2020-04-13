Doom mapping Manual
===================

This is a rework of manual from Doom Power (iddqd.ru)

Status
======

Work in progress

Building
========

[![Documentation Status](https://readthedocs.org/projects/cherepoc-s-doom-modding-tutorial/badge/?version=latest)](https://cherepoc-s-doom-modding-tutorial.readthedocs.io/ru/latest/?badge=latest)

The docs are built with [Sphinx](http://www.sphinx-doc.org/en/master/#). You need Python installed, use `pip` to install Sphinx:

    $ pip install sphinx

For more installation options [see here](http://www.sphinx-doc.org/en/master/usage/installation.html).

To build:

    $ make html

To auto-build on change detection, and serve the site for development:

    $ sphinx-autobuild source/ build/
