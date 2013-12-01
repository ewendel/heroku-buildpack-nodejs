Heroku Buildpack for Node.js
============================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for Node.js apps, customized by me to build the frontend app upon deploy.

This buildpack runs my own custom build script with node as the last command in the compil step: *node make.js*
