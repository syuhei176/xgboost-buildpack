Heroku buildpack: Python, Numpy, and Scipy (Python 2.7 only)
====================================================

This is fork from https://github.com/startupml/xgboost-buildpack

This is a custom [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for Python apps that use xgboost.


Usage
-----
For a new app:

    heroku create --buildpack https://github.com/syuhei176/xgboost-buildpack

For an existing app:

    heroku buildpacks:set https://github.com/syuhei176/xgboost-buildpack

