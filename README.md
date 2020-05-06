Heroku buildpack with ssm-env
=============================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
that allows one to run [ssm-env](https://github.com/remind101/ssm-env).

Usage
-----

Example usage:

    $ heroku buildpacks:add https://github.com/leibowitz/heroku-buildpack-ssm-env.git

    $ heroku config:add AWS_ACCESS_KEY_ID=<aws-access-key>
    $ heroku config:add AWS_SECRET_ACCESS_KEY=<aws-secret-access-key>
    $ heroku config:add AWS_DEFAULT_REGION=<default-aws-region>
