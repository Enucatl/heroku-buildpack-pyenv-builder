heroku-buildpack-pyenv-builder
==============================

Sets up an environment ready for pyenv to be used to install python versions
and other libs inside the .pyenv folder.
    
Use as a buildpack for
[python-versions](https://github.com/Enucatl/python-versions) in order to
build and upload to S3 pre-compiled python versions.

Why?
==============================

I find the environment of the default heroku python buildpack to be crazy
and difficult to adapt, or maybe I'm just too stupid to understand it.
