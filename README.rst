|Build Status| |PyPI Version| |PyPI License| |Python Versions| |Django Versions| |Read the Docs|

Django-CRUM
===========

Django-CRUM (Current Request User Middleware) captures the current request and
user in thread local storage.

It enables apps to check permissions, capture audit trails or otherwise access
the current request and user without requiring the request object to be passed
directly. It also offers a context manager to allow for temporarily
impersonating another user.

It provides a signal to extend the built-in function for getting the current
user, which could be helpful when using custom authentication methods or user
models.

Documentation can be found at `RTFD <http://django-crum.readthedocs.io/>`_.

It is tested against:
 * Django 1.8 (Python 2.7, 3.4 and 3.5)
 * Django 1.9 (Python 2.7, 3.4 and 3.5)
 * Django 1.10 (Python 2.7, 3.4 and 3.5)
 * Django 1.11 (Python 2.7, 3.4, 3.5 and 3.6)
 * Django 2.0 (Python 3.4, 3.5, 3.6 and 3.7)
 * Django 2.1 (Python 3.5, 3.6 and 3.7)
 * Django 2.2 (Python 3.5, 3.6, 3.7 and 3.8)
 * Django 3.0 (Python 3.6, 3.7 and 3.8)
 * Django master/3.1 (Python 3.6, 3.7 and 3.8)

.. |Build Status| image:: http://img.shields.io/travis/ninemoreminutes/django-crum.svg
   :target: https://travis-ci.org/ninemoreminutes/django-crum
.. |PyPI Version| image:: https://img.shields.io/pypi/v/django-crum.svg
   :target: https://pypi.python.org/pypi/django-crum/
.. |PyPI License| image:: https://img.shields.io/pypi/l/django-crum.svg
   :target: https://pypi.python.org/pypi/django-crum/
.. |Python Versions| image:: https://img.shields.io/pypi/pyversions/django-crum.svg
   :target: https://pypi.python.org/pypi/django-crum/
.. |Django Versions| image:: https://img.shields.io/pypi/djversions/django-crum.svg
   :target: https://pypi.org/project/django-crum/
.. |Read the Docs| image:: https://img.shields.io/readthedocs/django-crum.svg
   :target: http://django-crum.readthedocs.io/
