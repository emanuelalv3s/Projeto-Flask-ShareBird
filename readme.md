Flask
=====

Flask is a lightweight [WSGI](https://wsgi.readthedocs.io/) web application framework. It is designed
to make getting started quick and easy, with the ability to scale up to
complex applications. 

Flask offers suggestions, but doesn't enforce any dependencies or
project layout. It is up to the developer to choose the tools and
libraries they want to use. There are many extensions provided by the
community that make adding new functionality easy.


Installing
----------

Install and update using [pip](https://pip.pypa.io/en/stable/getting-started/):
```text
    $ pip install -U Flask
```

A Simple Example
----------------

```python

    # save this as app.py
    from flask import Flask

    app = Flask(__name__)

    @app.route("/")
    def hello():
        return "Hello, World!"
```

```text
    $ flask run
      * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```


Links
-----

-   PyPI Releases: https://pypi.org/project/Flask/
-   Source Code: https://github.com/emanuelalv3s/Projeto-Flask-ShareBird/
