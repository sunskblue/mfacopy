mfacopy
===

.. image:: https://badge.fury.io/py/mfa.svg?
   :target: https://pypi.python.org/pypi/mfacopy
   :alt: Latest PyPI version

Multi-factor authentication on your command line.


Installation
------------

It is available on PyPI__, so you can install it using ``pip``.

.. code-block:: console

   $ pip install mfacopy

__ https://pypi.python.org/pypi/mfacopy


Getting started
---------------

``mfacopy`` uses the system keyring service to store keys:

* Mac OS X Keychain
* Linux Secret Service
* Windows Credential Vault

Add key and value to the key store:

.. code-block:: console

   $ mfacopy set github f5347bieka5hcg5u

Get the value for a key:

.. code-block:: console

   $ mfacopy get github
   f5347bieka5hcg5u

Generate a one-time password:

.. code-block:: console

   $ mfacopy otp github
   925370


Author and license
------------------

`sunskblue`__ wrote ``mfacopy``.
It is licensed under the terms of the MIT_ license.

__ http://limeburst.net
.. _MIT: http://opensource.org/licenses/MIT


Changelog
---------

Version 0.0.1
`````````````

First alpha release.  Released on September 27, 2014.
