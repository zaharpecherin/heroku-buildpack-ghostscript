# Heroku Buildpack for Ghostscript

Currently installs Ghostscript 9.22 on Heroku Cedar.

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/sumeetattree/heroku-buildpack-ghostscript.git
    
    # Push changes to deploy
    $ git push

    # This version of ghostscript will end up deployed at /app/vendor/gs/bin/gs
    # So you _may_ want to set an environment variable to let your app know where it is. e.g.
    $ heroku config:set GS_PATH=/app/vendor/gs/bin/gs