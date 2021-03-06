*********************
Roadbuster
*********************

Overview
============
A lightweight django project with helper management commands to speed up djangocms development/test workflow (especially django_moderation).


Extras
---------
1) settings.py has all the necessary setups in INSTALLED_APP
2) django-su is installed, allowing us to switch easily between admin users


Installation & Setup
============

This assumes you have a python virtual environment setup with djangocms installed. If not run:

```
    mkvirtualenv roadbuster
    pip install -r requirements.txt
```

Then, pip install the plugin/application under test/development (e.g django_moderation) using ```pip -e <path_to_plugin>```


Usage
==========

1) To reset you database and re-populate it with CMS Pages and Moderation Workflows run:

``` 
    ./reload_db.sh
```


Contribution
=============

Please add more management commands as you see fit.