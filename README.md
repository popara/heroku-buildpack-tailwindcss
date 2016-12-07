Heroku buildpack: Dropbox CLI (dbxcli)
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of [Dropbox CLI (dbxcli)](https://github.com/dropbox/dbxcli).

Usage
-----

Example usage:

    [your app]
    $ heroku create --buildpack http://github.com/mallowlabs/heroku-buildpack-dbxcli.git
    $ heroku config:add DROPBOX_AUTH_TOKEN=<your token>
    $ git push heroku master
    $ heroku run dbxcli ls

