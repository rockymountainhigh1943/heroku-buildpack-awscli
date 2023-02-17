Heroku buildpack for the AWS CLI
================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
that allows one to run AWS CLI in a dyno alongside application code.

Usage
-----

Example usage:

    $ heroku buildpacks:add https://github.com/rockymountainhigh1943/heroku-buildpack-awscli.git

    $ heroku config:add AWS_ACCESS_KEY_ID=<aws-access-key>
    $ heroku config:add AWS_SECRET_ACCESS_KEY=<aws-secret-access-key>
    $ heroku config:add AWS_DEFAULT_REGION=<default-aws-region>
