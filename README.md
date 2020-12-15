# s4s-discovery

After `git clone`, or changing branches:
(if `git clone --recurse-submodules git@github.com:...` was not run)
```sh
git submodule update --init
```

## Local development:

Rebuild images in submodules:
```sh
docker-compose build
```


Run all services:
```sh
docker-compose up
```


Shut down all services:
```sh
docker-compose down
```
