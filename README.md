# Submodule notes

1. clone this repo w/ submodules
```
$ git clone --recurse-submodules cflynn07/jide-development
```

2. see which commits were added to submodules
```
$ git diff --submodule
```

3. Pull jide-development and update submodules
```
$ git pull
$ git submodule update --init --recursive
```
