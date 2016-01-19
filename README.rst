python-emailage
====================

.. image:: https://travis-ci.org/radzhome/python-emailage.svg?branch=master
    :target: https://travis-ci.org/radzhome/python-emailage

Python emailAge integration wrapper using `requests <https://github.com/kennethreitz/requests>`_.


Installation
------------

Via pip:

    pip install emailage

Example Usage
-------------

.. code:: python

    import emailage
    emailage.api.get_emailage_score('wang@emailage.com', ip='142.136.211.118', customer_key='<key>', secret_token='<token>')


TODO
----

* re-organize package, i.e. emailage.get_score()
* sphinx documentation

Legal
-----

This software is licensed under the BSD License.

This software is not authored by, endorsed by, or in any way affiliated with
emailAge Corp.

