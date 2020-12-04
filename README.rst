========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/inferiotscript/badge/?style=flat
    :target: https://readthedocs.org/projects/inferiotscript
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/prafulmaka/inferiotscript.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/prafulmaka/inferiotscript

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/prafulmaka/inferiotscript?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/prafulmaka/inferiotscript

.. |requires| image:: https://requires.io/github/prafulmaka/inferiotscript/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/prafulmaka/inferiotscript/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/prafulmaka/inferiotscript/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/prafulmaka/inferiotscript

.. |version| image:: https://img.shields.io/pypi/v/inferiot.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/inferiot

.. |wheel| image:: https://img.shields.io/pypi/wheel/inferiot.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/inferiot

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/inferiot.svg
    :alt: Supported versions
    :target: https://pypi.org/project/inferiot

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/inferiot.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/inferiot

.. |commits-since| image:: https://img.shields.io/github/commits-since/prafulmaka/inferiotscript/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/prafulmaka/inferiotscript/compare/v0.1.0...master



.. end-badges

Connect to Infer IoT Center using Python

* Free software: MIT license

Installation
============

::

    pip install inferiot

You can also install the in-development version with::

    pip install https://github.com/prafulmaka/inferiotscript/archive/master.zip


Documentation
=============


https://inferiotscript.readthedocs.io/


Development
===========

To run all the tests run::

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
