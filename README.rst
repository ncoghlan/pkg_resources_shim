Installable pkg_resources shim
==============================

The ``pkg_resources`` library is actually provided by the ``setuptools``
distribution package on PyPI.

This is just an installable ``pkg_resources`` shim that ensures that running
``pip install pkg_resources`` will install ``setuptools``, rather than
anything else.
