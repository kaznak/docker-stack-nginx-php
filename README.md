
# docker stack : nginx + php

## Usage

~~~
docker stack deploy -c stack.yml php
~~~

You can specify the application path by an environment variable.

~~~
APPD=./wordpress docker stack deploy -c stack.yml php
~~~

## Reference
+ [php](https://hub.docker.com/_/php/)
+ [nginx](https://hub.docker.com/_/nginx/)
