Installing this project
=======================

The easiest way to get this project installed with all its dependencies
is to use buildout. First run ``bootstrap.py`` with a clean Python such
as from a virtualenv::

  $ python bootstrap.py

Then run::

  $ bin/buildout

to get everything installed.

To build the HTML documentation you can now do::

  $ bin/sphinxbuilder

The resulting HTML is installed under ``doc/build/html``.
