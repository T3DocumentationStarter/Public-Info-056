.. include:: ../Includes.txt


.. _installation:

============
Installation
============

TYPO3 v8
========

To enable `rte_ckeditor` on an existing installation
in TYPO3 v8, disable `rtehtmlarea` and enable `rte_ckeditor`.

TYPO3 v9 and higher
===================

For installations since TYPO3 version 9, `rte_ckeditor` is activated by
default and ships with a default configuration for editors.

If you installed TYPO3 via composer with "subtree split", you must install
the extension, for example:

.. code-block:: bash

   composer require typo3/cms-rte-ckeditor:~9.0.0

See :ref:`t3coreapi:extension-install` in TYPO3 Explained for more information
about installing extensions.

.. todo: screenshot of extension manager?
