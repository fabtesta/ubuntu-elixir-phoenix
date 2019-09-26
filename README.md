Docker Ubuntu 18 LTS - Erlang/Elixir - Phoenix Framework
==============
## Introduction 

A docker container with the Phoenix Framework development environment.

[Phoenix Framework Homepage](https://phoenixframework.org/)
## Quickstart

* Create app from base template:
```
docker run --rm -v $(pwd):/code fabtesta/ubuntu-elixir-phoenix mix phx.new my_new_app
cd my_new_app
docker run --rm -v $(pwd):/code fabtesta/ubuntu-elixir-phoenix mix deps.get
```
* Start an interactive shell to configure your new app (ex. mix ecto.create):
```
docker run -it --rm -v $(pwd):/code fabtesta/ubuntu-elixir-phoenix /bin/bash
```
* Start server and watch code:
```
docker run -it --rm -v $(pwd):/code mix phx.server
```

## Useful links

[Github remote](https://github.com/fabtesta/ubuntu-elixir-phoenix)

[Docker Hub repo](https://hub.docker.com/r/fabtesta/ubuntu-elixir-phoenix)