heroku-redirect
===============

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

A simple Heroku application that redirects all incoming requests to another location. Use the `LOCATION` config var to configure the location where the requests are redirected to. For example,

    heroku config:set LOCATION=https://www.example.com

If you want the redirects to preserve path, set the `PRESERVE_PATH` config var. By default paths are not preserved.
