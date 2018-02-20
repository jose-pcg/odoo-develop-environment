Virtualenvwrapper is a tool that make everything easier with virtuealenvs.

How to
======

Install:
---------
```
$ sudo pip install virtualenvwrapper
```
Setup:
---------
Edit your `.bash_profile` file and add this lines:
```
export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source `which virtualenvwrapper.sh`
```
Usage:
------
To create an environment, type:
```
$ mkvirtualenv odoo10
```
To work on that environment just type:
```
$ workon odoo10
```
To exit the environment:
```
$ deactivate
```
