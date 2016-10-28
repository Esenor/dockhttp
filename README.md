# DockHttp #

Simple HTTPD container to running simple HTML project.

## Install ##

    # Build container
    docker-compose -f docker_compose.yml build
    # Run container
    docker-compose -f docker_compose.yml up -d
    # Open http://dockerhost:8127/index.html

## Use ##

Move html file in `src` folder.
