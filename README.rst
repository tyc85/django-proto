django-proto
=======================

Features
---------

* For Django 1.7
* Twitter Bootstrap_ 3
* AngularJS_

.. _Bootstrap: https://github.com/twbs/bootstrap
.. _AngularJS: https://github.com/angular/angular.js

mkvirtualenv project_name

pip install django

    django-admin.py startproject --template=https://github.com/privgrey/django-prototype/archive/master.zip --extension=py,rst,html project_name

Set Environment Variable

if you are developing locally
cp settings/base.py settings/dev_yourname.py


export DJANGO_SETTINGS_MODULE=project_name.settings.environment_type



Add custom environment variables to your postactivate script

# an example of setting environment variables for a django project to your virtual env
cat >> ~/.virtualenvs/project_name/bin/postactivate

export DJANGO_SETTINGS_MODULE="project.settings"
