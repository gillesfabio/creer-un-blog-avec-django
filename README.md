Source code of my french tutorial: "Créer un blog avec Django"
==============================================================

Tutorial URL: http://gillesfabio.com/blog/2009/01/29/creer-un-blog-avec-django/

Information
-----------

This version runs on Django 1.1.

The tutorial has been updated to run on Django 1.2. 

* URL: http://gillesfabio.com/blog/2010/07/22/creer-un-blog-avec-django-1-2/
* Repository: http://github.com/gillesfabio/creer-un-blog-avec-django-1.2 

Installation
------------

Grab the source::

    $ git clone git://github.com/gillesfabio/creer-un-blog-avec-django.git

Go in the project's folder::

    $ cd creer-un-blog-avec-django/website

Change some settings if you need and synchronize the database::

    $ python manage.py syncdb

Load the fixtures::

    $ python manage.py loaddata test_data
    
Run the server::

    $ python manage.py runserver
    
That's all.
