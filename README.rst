scikit-surgerytutorial02-test
===============================

.. image:: https://github.com/mxochicale/scikit-surgerytutorial02-test.git/raw/master/project-icon.png
   :height: 128px
   :width: 128px
   :target: https://github.com/mxochicale/scikit-surgerytutorial02-test.git
   :alt: Logo

.. image:: https://github.com/mxochicale/scikit-surgerytutorial02-test.git/badges/master/build.svg
   :target: https://github.com/mxochicale/scikit-surgerytutorial02-test.git/pipelines
   :alt: GitLab-CI test status

.. image:: https://github.com/mxochicale/scikit-surgerytutorial02-test.git/badges/master/coverage.svg
    :target: https://github.com/mxochicale/scikit-surgerytutorial02-test.git/commits/master
    :alt: Test coverage

.. image:: https://readthedocs.org/projects/scikit-surgerytutorial02-test/badge/?version=latest
    :target: http://scikit-surgerytutorial02-test.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status



Author: Miguel Xochicale

scikit-surgerytutorial02-test is part of the `SciKit-Surgery`_ software project, developed at the `Wellcome EPSRC Centre for Interventional and Surgical Sciences`_, part of `University College London (UCL)`_.

scikit-surgerytutorial02-test is tested on Python 3.7 but should support other modern Python versions.

scikit-surgerytutorial02-test is currently a demo project, which will add/multiply two numbers. Example usage:

::

    python scikit-surgerytutorial02-test.py 5 8
    python scikit-surgerytutorial02-test.py 3 6 --multiply

Please explore the project structure, and implement your own functionality.

Developing
----------

Cloning
^^^^^^^

You can clone the repository using the following command:

::

    git clone https://github.com/mxochicale/scikit-surgerytutorial02-test.git


Running tests
^^^^^^^^^^^^^
Pytest is used for running unit tests:
::

    pip install pytest
    python -m pytest


Linting
^^^^^^^

This code conforms to the PEP8 standard. Pylint can be used to analyse the code:

::

    pip install pylint
    pylint --rcfile=tests/pylintrc scikit-surgerytutorial02-test


Installing
----------

You can pip install directly from the repository as follows:

::

    pip install git+https://github.com/mxochicale/scikit-surgerytutorial02-test.git



Contributing
^^^^^^^^^^^^

Please see the `contributing guidelines`_.


Useful links
^^^^^^^^^^^^

* `Source code repository`_
* `Documentation`_


Licensing and copyright
-----------------------

Copyright 2023 University College London.
scikit-surgerytutorial02-test is released under the BSD-3 license. Please see the `license file`_ for details.


Acknowledgements
----------------

Supported by `Wellcome`_ and `EPSRC`_.


.. _`Wellcome EPSRC Centre for Interventional and Surgical Sciences`: http://www.ucl.ac.uk/weiss
.. _`source code repository`: https://github.com/mxochicale/scikit-surgerytutorial02-test.git
.. _`Documentation`: https://scikit-surgerytutorial02-test.readthedocs.io
.. _`SciKit-Surgery`: https://github.com/SciKit-Surgery
.. _`University College London (UCL)`: http://www.ucl.ac.uk/
.. _`Wellcome`: https://wellcome.ac.uk/
.. _`EPSRC`: https://www.epsrc.ac.uk/
.. _`contributing guidelines`: https://github.com/mxochicale/scikit-surgerytutorial02-test.git/blob/master/CONTRIBUTING.rst
.. _`license file`: https://github.com/mxochicale/scikit-surgerytutorial02-test.git/blob/master/LICENSE

