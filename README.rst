===================
djangocms-page-meta
===================

.. image:: https://img.shields.io/pypi/v/djangocms-page-meta.svg
        :target: https://pypi.python.org/pypi/djangocms-page-meta
        :alt: Latest PyPI version

.. image:: https://img.shields.io/travis/nephila/djangocms-page-meta.svg
        :target: https://travis-ci.org/nephila/djangocms-page-meta
        :alt: Latest Travis CI build status

.. image:: https://img.shields.io/pypi/dm/djangocms-page-meta.svg
        :target: https://pypi.python.org/pypi/djangocms-page-meta
        :alt: Monthly downloads

.. image:: https://coveralls.io/repos/nephila/djangocms-page-meta/badge.png
        :target: https://coveralls.io/r/nephila/djangocms-page-meta
        :alt: Test coverage

Tagged pages for django CMS 3

**********
Quickstart
**********

#. Install djangocms-page-meta::

        $ pip install djangocms-page-meta

   or from the repository::

        pip install -e git+https://github.com/nephila/djangocms-page-meta#egg=djangocms-page-meta

#. Then add it to INSTALLED_APPS along with its dependencies::

        'filer',
        'meta',
        'meta_mixin',
        'djangocms_page_meta',

#. Synchronize the database with syncdb::

        $ python manage.py syncdb

   or migrate::

        $ python manage.py migrate

#. Configuration:

    There is no special configuration for djangocms-page-meta, but make sure you set the necessary configuration for `django-meta`_.

#. That's all!

Dependencies
============

* `django-filer`_ >= 0.9.5
* `django-meta`_  >= 0.1.0
* `django-meta-mixin`_  >= 0.1.0

.. _django-filer: https://pypi.python.org/pypi/django-filer
.. _django-meta: https://pypi.python.org/pypi/django-meta
.. _django-meta-mixin: https://pypi.python.org/pypi/django-meta-mixin


Python 3
========

`djangocms-page-meta` per-se is fully Python 3 compatible; django-filer is
python 3 compatible starting from version 0.9.6.

*************
Documentation
*************

For package documentation see http://djangocms-page-meta.readthedocs.org/.

