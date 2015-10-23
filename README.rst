gogo
====

gogo - Go everywhere you want to go, never get lost in Go world (again).

Why
---

Because we always remember the package name, not its author's GitHub account.

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
- port to Golang
