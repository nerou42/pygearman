# pygearman

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/nerou42/pygearman/ci.yml)
[![Quality Gate Status](https://sonarqube.nerou.de/api/project_badges/measure?project=nerou42_pygearman_6c41fdb4-7222-4cd7-ab98-0f7ac281c99e&metric=alert_status&token=sqb_e16e31f4ab67e7df1e72f88d57fde5e98e411670)](https://sonarqube.nerou.de/dashboard?id=nerou42_pygearman_6c41fdb4-7222-4cd7-ab98-0f7ac281c99e)
![GitHub Release](https://img.shields.io/github/v/release/nerou42/pygearman?display_name=tag&label=latest%20release&color=blue)

This is a Gearman API written in Python -- client, worker and admin client interfaces.

For information about Gearman and a C-based Gearman server, see [http://gearman.org/](http://gearman.org/).

This is a fork of the [wellcomecollection/python-gearman](https://github.com/wellcomecollection/python-gearman) project, which is a fork of the original [Yelp/python-gearman](https://github.com/Yelp/python-gearman) project.
You can use this library if you have an existing project that uses python-gearman or gearman3 and you want to upgrade to Python 3.9+.

This fork fixes the compatibility to Python 3.9+.

## Installation

This library is published on PyPI as [pygearman](https://pypi.org/project/pygearman/).
You can install it using pip:

```shell
pip install pygearman
```

The library is tested with Python 3.9 to 3.13.


## Usage

This is a drop-in replacement for the 2.x python-gearman and 0.2 gearman3 libraries.
There are docs at [https://pythonhosted.org/gearman/](https://pythonhosted.org/gearman/).


## Development

wellcomecollection created their fork so they'd have a Python 3-compatible version of Gearman to use in [Archivematica](https://github.com/artefactual/archivematica).

New patches should come with tests and a release note.

See [developers.rst](developers.rst) for more notes on development, and in particular instructions for creating pull requests.


## Further links

- Changelog for pygearman: see [changes.rst](changes.rst).

- 2.x source: [https://github.com/Yelp/python-gearman/](https://github.com/Yelp/python-gearman/)
- 2.x documentation: [https://packages.python.org/gearman/](https://packages.python.org/gearman/)

- 1.x source [https://github.com/samuel/python-gearman/](https://github.com/samuel/python-gearman/)
- 1.x documentation [https://github.com/samuel/python-gearman/tree/master/docs/](https://github.com/samuel/python-gearman/tree/master/docs/)
