Python virtualenv creates isolated python copies in order to have your
projects running in its own python version and using its specific packages versions.

How to:
=======

Install:
----
```
$ sudo pip install virtualenv
```

Create your python environment
------------------------------

First create a file to store your environments
```
$ mkdir ~/.virtualenvs
```
Create your environment
```
$ virtualenv --python=`which python2.7` ~/.virtualenvs/odoo10
```
Note: See the `which python2.7` thing? Here you can specify your python version. Eg: --python=`which python3.5`

Access to your new environment:
-------------------------------
```
$ source ~/.virtualenvs/odoo10/bin/activate
```
After that, you can check your python version
```
$ python -V
```
Or list the packages installed in that environment
```
$ pip list
```
Close the environment:
----------------------
Just type
```
$ deactivate
```
