Installation
=============

The orrey helpers require several python numerical libraries. However,
the setup is configured to install all dependencies already.

If conda is setup (recommended), run this first to install the packages
available in conda with conda::

  conda install pandas seaborn

To install (regardless of whether you have conda or not), run::

  pip install orrey

If you don't run the ``conda install`` first, pip will try to install the required
packages on its own. Running ``conda install`` first is preferred (easier
environment management, fewer possible version problems, easier uninstallation)
but the ``pip install`` should work as well.
