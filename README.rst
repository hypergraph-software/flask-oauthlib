Flask-OAuthlib
==============

Flask-OAuthlib is an extension to Flask that allows you to interact with
remote OAuth enabled applications. On the client site, it is a replacement
for Flask-OAuth. But it does more than that, it also helps you to create
OAuth providers.

Flask-OAuthlib relies on oauthlib_.

.. _oauthlib: https://github.com/idan/oauthlib

Features
--------

- Support for OAuth 1.0a, 1.0, 1.1, OAuth2 client
- Friendly API (same as Flask-OAuth)
- Direct integration with Flask
- Basic support for remote method invocation of RESTful APIs
- Support OAuth1 provider with HMAC and RSA signature
- Support OAuth2 provider with Bearer token

Installation
------------

Installing flask-oauthlib is simple with pip_::

    $ pip install Flask-OAuthlib

If you don't have pip installed, try with easy_install::

    $ easy_install Flask-OAuthlib

.. _pip: http://www.pip-installer.org/


Additional Notes
----------------

We keep documentation at `flask-oauthlib@readthedocs`_.

.. _`flask-oauthlib@readthedocs`: https://flask-oauthlib.readthedocs.io

If you are only interested in the client part, you can find some examples
in the ``example`` directory.
