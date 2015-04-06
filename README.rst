pickleDB
--------

Fork of [PickleDB](https://bitbucket.org/patx/pickledb) and [olivierlemoal](https://github.com/olivierlemoal/) with support for Python 3 and UTF-8.
Compatible Python >= 2.6 and 3.

pickleDB is lightweight, fast, and simple database based on Python's own 
json module. And it's BSD licensed!


pickleDB is Fun
```````````````

    >>> import pickledb

    >>> db = pickledb.load('test.db', False)

    >>> db.set('key', 'value')

    >>> db.get('key')
    'value'

    >>> db.dump()
    True


Easy to Install
```````````````

    $ pip install pickledb


Links
`````

* `website <http://packages.python.org/pickleDB/>`_
* `documentation <http://packages.python.org/pickleDB/commands.html>`_
* `pypi
  <http://pypi.python.org/pypi/pickleDB>`_
