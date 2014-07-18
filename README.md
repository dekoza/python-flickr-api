Python Async Flickr API
-----------------------

This is a fork of Alexis Mignon's python-flickr-api adapted to work asynchronously under Tornado framework.

As complete as possible implementation of Flickr API.

The project provides an almost exhaustive access to the Flickr API, through an *object oriented* Python interface.

The project is still at an early stage and requires a lot of testing.
Any help including bug reports is appreciated.

Main features
-------------
  *  Object Oriented implementation
  *  (Almost) comprehensive implementation
  *  uses OAuth for authentication
  *  context sensitive objects (depending on the query context, objects may exhibit different attributes)
  *  An interface for direct seamless calls to the Flickr API.
  *  A (django-complient) caching mechanism

Requires
--------
  * python >= 2.6.5 
  * python-oauth (or the python module from http://code.google.com/p/oauth/)
  * tornado

Installation
------------

### From source

```bash
$ git clone https://github.com/bryndin/tornado-flickr-api.git
$ cd tornado-flickr-api
$ python setup.py install --user  # to install in the user directory (~/.local)
$ sudo python setup.py install    # to install globally
```

Tutorial
--------
A short tutorial is available in the [Wiki section](https://github.com/alexis-mignon/tornado-flickr-api/wiki/Tutorial).