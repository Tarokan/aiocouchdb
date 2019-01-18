==========
aiocouchdb
==========

:source: https://github.com/aio-libs/aiocouchdb
:documentation: http://aiocouchdb.readthedocs.org/en/latest/
:license: BSD

**Installation**
pip install git+git://github.com/Tarokan/aiocouchdb 

CouchDB client built on top of `aiohttp`_ and made for `asyncio`_.

Current status: **beta**. `aiocouchdb` has all CouchDB API implements up to
1.6.1 release, and the ability to use Mango Queries, and create Mango Indices.

However, it may lack of some usability and stability bits, but
work is in progress. Feel free to `send pull request`_ or `open issue`_ if
you'd found something that should be fixed, however updates will be limited.

**Features**

aiocouchdb now supports a create_doc() method that can be called on a database instance, which takes in a JSON or JSON string, and additional optional parameters.

- Modern CouchDB client for Python 3.3+ based on `aiohttp`_
- Complete CouchDB API support (JSON and Multipart) up to 1.6.1 version
- Multiuser workflow with Basic Auth, Cookie, Proxy and OAuth support
- Stateless behavior
- Stream-like handling views, changes feeds and bulk docs upload

Requirements
============

- Python 3.3+
- `aiohttp`_ limited coverage, tested on 3.2.1, at least 3.0.0
- `oauthlib`_ (optional)

.. _aiohttp: https://github.com/aio-libs/aiohttp
.. _asyncio: https://docs.python.org/3/library/asyncio.html
.. _oauthlib: https://github.com/idan/oauthlib

.. _open issue: https://github.com/aio-libs/aiocouchdb/issues
.. _send pull request: https://github.com/aio-libs/aiocouchdb/pulls
