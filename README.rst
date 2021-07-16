==============
django-groups2
==============

Capabilities
------------

* Adds a `Group2` model to improve upon the django.auth.Group
* Adds a `Group2Kind` model to have Group kinds
* Adds various needed properties to `Group2`
* Adds a proper hierarchy using https://github.com/django-treebeard/django-treebeard (editable through django-admin)
* Has an one-to-one relationship with builtin `Group` which is used to keep user members and any needed permissions
* Allows user membership to be edited through django-admin

v.0.1.0
-------

- Initial version


