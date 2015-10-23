gogo
====

gogo - never get lost (again) in Go world.

Because you always remember the package name, not his GitHub account.

Usage
-----

Find and cd to directory of a package::

  cd `gogo logrus`
  cd `gogo echo`

Add import path from inside vim::

  :r ! gogo govalidator

Of course, the package must already on your disk, and the ``$GOPATH`` is
correctly set.

Installtion
-----------

Run setup.py file::

  python setup.py install

TODO
----

- support Py3
- handle non-github repo (E.g yaml)
