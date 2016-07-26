# pydoc27fork
A fork of [pydoc.py](https://docs.python.org/2.7/library/pydoc.html) in Python 2.7 with the following features:

1. Supports specified `hostname` using `-h` option, which defaults to `localhost` therefore be compatible with original edition. For instance, to run pydoc listening to all out-coming requests:
```
$ python pydoc27fork.py -h 0.0.0.0 -p 8888
```
