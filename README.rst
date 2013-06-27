=============================
django-registration-bootstrap
=============================

Bootstrap friendly pieces for django-registration

Installation
============

First, get and install django-registration

Then get django-registration-bootstrap from PyPI:

.. code-block:: bash

    $ pip install django-registration-bootstrap==0.1.0
    

Into the settings file, add the following to ``INSTALLED_APPS``:

.. code-block:: python

    INSTALLED_APPS = (
        # ... everything else
        
        # Add the templates via INSTALLED_APPS
        'registration_bootstrap',
        
        # only add crispy_forms if you aren't already using it
        'crispy_forms'
    )

Requirements
============

* Django 1.5+
* Python 2.7+ or Python 3.3+
* django-registration 1+
* django-crispy-forms 1.3.2+

History
=======

0.1 (2013-06-27)

  * Simple registration only
  * Discovery that no one had this done and deployed to PyPI.