# Heroku Buildpack for Ghostscript

Installs Ghostscript 9.50 on Heroku

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/sdglhm/heroku-buildpack-ghostscript.git
    
    # Push changes to deploy
    $ git push

    # This version of ghostscript will end up deployed at /app/vendor/ghostscript/bin/gs
    
