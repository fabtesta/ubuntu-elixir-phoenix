Docker Ubuntu 18 LTS - Erlang/Elixir - Phoenix Framework
==============
## Introduction 

Docker container used for develop Phoenix Framework application.

[Phoenix Framework Homepage](https://phoenixframework.org/)
## Quickstart

* Create app from base template:
```
docker run --rm -v $(pwd):/code fabtesta/ubuntu-elixir-phoenix mix phx.new my_new_app
```
* Start an interactive shell to configure your new app:
```
docker run -it --rm -v $(pwd):/code fabtesta/ubuntu-elixir-phoenix /bin/bash
```
* Start server and watch code:
```
docker run -it --rm -v $(pwd):/code mix phx.server /code/my_new_app
```

## Useful links

[Github remote](https://github.com/fabtesta/ubuntu-elixir-phoenix)

[Docker Hub repo](https://hub.docker.com/r/fabtesta/ubuntu-elixir-phoenix)