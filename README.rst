pygearman
==============

This is a Gearman API written in Python -- client, worker and admin client interfaces.

For information about Gearman and a C-based Gearman server, see `<http://gearman.org/>`_.

This is a fork of the `wellcomecollection/python-gearman <https://github.com/wellcomecollection/python-gearman>`_ project, which is a fork of the original `Yelp/python-gearman <https://github.com/Yelp/python-gearman>`_ project.
You can use this library if you have an existing project that uses python-gearman or gearman3 and you want to upgrade to Python 3.9+.

This fork fixes the compatibility to Python 3.9+.

Installation
************

This library is published on PyPI as `pygearman <https://pypi.org/project/pygearman/>`_.
You can install it using pip:

.. code-block::

   pip install pygearman

The library is tested with Python 3.9 to 3.13.


Usage
*****

This is a drop-in replacement for the 2.x python-gearman and 0.2 gearman3 libraries.
There are docs at `<https://pythonhosted.org/gearman/>`_.


Development
***********

wellcomecollection created their fork so they'd have a Python 3-compatible version of Gearman to use in `Archivematica <https://github.com/artefactual/archivematica>`_.

New patches should come with tests and a release note.

See `<developers.rst>`_ for more notes on development, and in particular instructions for creating pull requests.


Further links
*************

* Changelog for pygearman: see `<changes.rst>`_.

* 2.x source: `<https://github.com/Yelp/python-gearman/>`_
* 2.x documentation: `<https://packages.python.org/gearman/>`_

* 1.x source `<https://github.com/samuel/python-gearman/>`_
* 1.x documentation `<https://github.com/samuel/python-gearman/tree/master/docs/>`_
