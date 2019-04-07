# Sentry Taiga

A plugin for [Sentry](http://getsentry.com) which allows issue creation in your [Taiga](https://taiga.io) projects from errors.

## Install

Install the package via `pip`

```
pip install sentry-taiga
```

or `easy_install`

```
easy_install sentry-taiga
```

And restart Sentry

## Configure

Once enabled you can configure your settings for the project. You can also include default tags you wish to apply to issues created.

I would recommend you create a specific user for Taiga to use with only `Reporter` privileges to your projects.

Bugs & Issues
-------------

If you find something that doesn't work please create an issue or even better fix it and submit a pull request!

Dependencies
------------

* [python-taiga](https://pypi.python.org/pypi/python-taiga)

License
-------

MIT License. See [LICENSE](https://github.com/rochsystems/sentry-taiga/blob/master/LICENSE) file.

Based on [sentry-gitlab](https://github.com/pancentric/sentry-gitlab) from Pancentric Ltd.

