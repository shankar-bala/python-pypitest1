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
.. |docs| image:: https://readthedocs.org/projects/python-pypitest1/badge/?style=flat
    :target: https://readthedocs.org/projects/python-pypitest1
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/shankar-bala/python-pypitest1.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/shankar-bala/python-pypitest1

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/shankar-bala/python-pypitest1?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/shankar-bala/python-pypitest1

.. |requires| image:: https://requires.io/github/shankar-bala/python-pypitest1/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/shankar-bala/python-pypitest1/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/shankar-bala/python-pypitest1/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/shankar-bala/python-pypitest1

.. |version| image:: https://img.shields.io/pypi/v/pypitest1.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pypitest1

.. |wheel| image:: https://img.shields.io/pypi/wheel/pypitest1.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pypitest1

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pypitest1.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pypitest1

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pypitest1.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pypitest1

.. |commits-since| image:: https://img.shields.io/github/commits-since/shankar-bala/python-pypitest1/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/shankar-bala/python-pypitest1/compare/v0.0.0...master



.. end-badges

Test project to upload packages to pypi.

* Free software: Apache Software License 2.0

Installation
============

::

    pip install pypitest1

You can also install the in-development version with::

    pip install https://github.com/shankar-bala/python-pypitest1/archive/master.zip


Documentation
=============


https://python-pypitest1.readthedocs.io/


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
