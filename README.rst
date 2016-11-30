========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |codecov|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-roscoe/badge/?style=flat
    :target: https://readthedocs.org/projects/python-roscoe
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/sesamemucho/python-roscoe.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/sesamemucho/python-roscoe

.. |requires| image:: https://requires.io/github/sesamemucho/python-roscoe/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/sesamemucho/python-roscoe/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/sesamemucho/python-roscoe/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/sesamemucho/python-roscoe

.. |version| image:: https://img.shields.io/pypi/v/roscoe.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/roscoe

.. |downloads| image:: https://img.shields.io/pypi/dm/roscoe.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/roscoe

.. |wheel| image:: https://img.shields.io/pypi/wheel/roscoe.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/roscoe

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/roscoe.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/roscoe

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/roscoe.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/roscoe


.. end-badges

Skeleton project for automated testing of embedded projects

* Free software: BSD license

Installation
============

::

    pip install roscoe

Documentation
=============

https://python-roscoe.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
