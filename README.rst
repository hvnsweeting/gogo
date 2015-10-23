gogo
====

gogo - Go everywhere you want to go, never get lost in Go world (again).

Why
---

Because we always remember the package name, not its author's GitHub account.

Usage
-----

Print out full path of given go package::

  $ gogo yaml.v2
  $HOME/src/gopkg.in/yaml.v2
  $ gogo logrus
  $HOME/src/github.com/Sirupsen/logrus

Print out import path of given go package::

  $ gogo -i yaml.v2
  gopkg.in/yaml.v2
  $ gogo -i logrus
  github.com/Sirupsen/logrus

Find and cd to directory of a package::

  cd `gogo docker`

Add import path from inside vim::

  :r ! gogo logrus

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
