Introduction
============

This document describes how to add ZEO to the Plone 4 buildout described in
README.txt

Adding ZEO
----------

To add ZEO, do this::

    $ bin/buildout -c zeo.cfg
    $ bin/supervisord

Check out http://localhost:8080. In particular, check out:
http://localhost:8080/Control_Panel/Database/main/manage_main to verify
zeostorage.

More info
---------

For more information about additional configuration options, please see:

- http://pypi.python.org/pypi/plone.recipe.zope2instance
- http://pypi.python.org/pypi/plone.recipe.zeoserver

Questions/Comments/Concerns? Email: aclark@aclark.net
