Confluent Stream Data Platform on Single Docker Container
=========================================================

Experimental docker images for running the
[Confluent Platform](http://confluent.io/docs/current/index.html).
These images are currently intended for development use, not for production use.

[![](https://badge.imagelayers.io/socialorra/confluent-platform:latest.svg)](https://imagelayers.io/?images=socialorra/confluent-platform:latest 'Get your own badge on imagelayers.io')

Building Images
---------------

For convenience, a `build.sh` script is provided.

A second script, `push.sh`, will push the generated images to Docker
Hub. First you'll need to be logged in:

    docker login --username=yourhubusername --password=yourpassword --email=youremail@company.com

then execute the script.
