django-flat-theme
=================

Description
-----------

**django-flat-theme** brings fresh air to the default Django Admin
interface which hasn't changed about 10 years from the very first version of
Django framework. This theme just makes UI modern and clean.

This app overrides default admin's CSS. All changes are about colors,
margins, sizes and icons. Nothing major.


Installation
------------

Install via pip:
``pip install django-flat-theme``

1. Put ``flat`` app in your *INSTALLED\_APPS* **before**
   ``django.contrib.admin``:

   ::

       INSTALLED_APPS = (
           ...
           'flat',
           'django.contrib.admin',
           ...
       )

2. That's it.

Compatibility
~~~~~~~~~~~~~

Works correct in Django 1.5+.

Font
~~~~

This theme uses `Roboto <http://www.google.com/fonts/specimen/Roboto>`__
font which is under Apache 2.0 licence.

Image icons were replaced with `Font Awesome <http://fortawesome.github.io/Font-Awesome/>`__
iconic font which is under GPL licence.


Testing
~~~~~~~

Tested in:

- IE8+ (looks OK in IE8 in terms of graceful degradation)
- FF30+ (Windows, Ubuntu, OSX)
- Chrome 35+ (Windows, Ubuntu, OSX)
- Safari 8 (OSX)

Screenshot Examples
~~~~~~~~~~~~~~~~~~~

**Login page** |1|

**Dashboard** |2|

**List of objects** |3|

**New object** |4|

.. |1| image:: https://cloud.githubusercontent.com/assets/209663/6742228/df94018a-ceaf-11e4-8be8-5f31f01512d4.png
.. |2| image:: https://cloud.githubusercontent.com/assets/209663/6742227/df93dade-ceaf-11e4-9b88-aacf33b4eb3c.png
.. |3| image:: https://cloud.githubusercontent.com/assets/209663/6742226/df93e556-ceaf-11e4-98ad-7c5b4871fc04.png
.. |4| image:: https://cloud.githubusercontent.com/assets/209663/6742225/df938d5e-ceaf-11e4-8d3d-8968a9c76c99.png

