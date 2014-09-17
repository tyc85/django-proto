django-proto
=======================

Features
---------

* For Django 1.7
* Twitter Bootstrap_ 3
* AngularJS_

.. _Bootstrap: https://github.com/twbs/bootstrap
.. _AngularJS: https://github.com/angular/angular.js

Usage
--------------------------

Name your project first::

    mkvirtualenv project_name

Install django::

    pip install django


To create the project, run the following command::

    django-admin.py startproject --template=https://github.com/privgrey/django-proto/archive/master.zip --extension=py,rst,html project_name




If you are one of the developement member, 
    cp settings/local.py settings/dev_yourname.py

Set Environment Variable
--------------------------
Set Django settings file before bootstraping::

    export DJANGO_SETTINGS_MODULE=project_name.settings.environment_type

Add custom environment variables to your postactivate script
--------------------------

Edit your virtualenvs/bin/postactivate::

    export DJANGO_SETTINGS_MODULE=project_name.settings.environment_type
