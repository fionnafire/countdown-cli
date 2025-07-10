countdown-cli
=============

|PyPI| |Status| |Python Version| |License|

|Tests| |Codecov|

|pre-commit| |Black|

.. |PyPI| image:: https://img.shields.io/pypi/v/countdown-cli.svg
   :target: https://pypi.org/project/countdown-cli/
   :alt: PyPI
.. |Status| image:: https://img.shields.io/pypi/status/countdown-cli.svg
   :target: https://pypi.org/project/countdown-cli/
   :alt: Status
.. |Python Version| image:: https://img.shields.io/pypi/pyversions/countdown-cli
   :target: https://pypi.org/project/countdown-cli
   :alt: Python Version
.. |License| image:: https://img.shields.io/pypi/l/countdown-cli
   :target: https://opensource.org/licenses/MIT
   :alt: License
.. |Tests| image:: https://github.com/treyhunner/countdown-cli/workflows/Tests/badge.svg
   :target: https://github.com/treyhunner/countdown-cli/actions?workflow=Tests
   :alt: Tests
.. |Codecov| image:: https://codecov.io/gh/treyhunner/countdown-cli/branch/main/graph/badge.svg
   :target: https://codecov.io/gh/treyhunner/countdown-cli
   :alt: Codecov
.. |pre-commit| image:: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white
   :target: https://github.com/pre-commit/pre-commit
   :alt: pre-commit
.. |Black| image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Black

**This is a fork of the original** `treyhunner/countdown-cli`_ **with additional features.**

This project is based on a `Python Morsels`_ exercise for a command-line countdown timer.
If you're working on that exercise right now, please **don't look at the source code** for this. 😉

|Logo|

.. |Logo| image:: https://raw.githubusercontent.com/treyhunner/countdown-cli/main/images/python-morsels-logo.png
   :target: https://www.pythonmorsels.com
   :width: 400
   :alt: an adorable snake taking a bite out of a cookie with the words Python Morsels next to it (Python Morsels logo)

Wondering how this package works?
**Don't look at the source code just yet!**
Instead, try implementing this package with the `Python Morsels "countdown" exercise <https://www.pythonmorsels.com/exercises/fc3be8467c634f978eae0c315f5677d1/>`_!


Features
--------

* Full-screen countdown timer, centered in the terminal window
* Command-line interface for Linux/Mac/Windows
* **Red end screen display when countdown reaches zero** (NEW in this fork)

|32:53|

|14:57|

.. |32:53| image:: https://raw.githubusercontent.com/treyhunner/countdown-cli/main/images/3253.png
   :width: 500
   :alt: 32:53 shown in large letters in center of an xterm window (black background with white text)

.. |14:57| image:: https://raw.githubusercontent.com/treyhunner/countdown-cli/main/images/1457.png
   :width: 500
   :alt: 14:57 shown in large letters in center of terminal window (light background with darker text)


What's New in This Fork
-----------------------

**Red End Screen**: When the countdown reaches zero, the timer now displays a prominent red "END" message on the screen, making it impossible to miss when time is up. This visual enhancement provides a clear, attention-grabbing indication that the countdown has finished.


Requirements
------------

* Python 3.7+


Installation
------------

You can install *countdown-cli* via pip_ from PyPI_:

.. code:: console

   $ python3 -m pip install countdown-cli


Contributing
------------

Contributions are very welcome.
To learn more, see the `Contributor Guide`_.


License
-------

Distributed under the terms of the `MIT license`_,
*countdown-cli* is free and open source software.


Issues
------

If you encounter any problems,
please `file an issue`_ along with a detailed description.


Credits
-------

This project was generated from `@cjolowicz`_'s `Hypermodern Python Cookiecutter`_ template.

This fork includes enhancements by `@fionnafire`_ including the red end screen feature.

.. _Python Morsels: https://www.pythonmorsels.com
.. _treyhunner/countdown-cli: https://github.com/treyhunner/countdown-cli
.. _@cjolowicz: https://github.com/cjolowicz
.. _@fionnafire: https://github.com/fionnafire
.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _MIT license: https://opensource.org/licenses/MIT
.. _PyPI: https://pypi.org/project/countdown-cli/
.. _Hypermodern Python Cookiecutter: https://github.com/cjolowicz/cookiecutter-hypermodern-python
.. _file an issue: https://github.com/fionnafire/countdown-cli/issues
.. _pip: https://pip.pypa.io/
.. github-only
.. _Contributor Guide: CONTRIBUTING.rst
