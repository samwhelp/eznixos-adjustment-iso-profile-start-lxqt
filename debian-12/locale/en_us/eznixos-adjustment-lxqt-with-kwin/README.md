

# EznixOs Adjustment


## Link

* [https://github.com/PapirusDevelopmentTeam/arc-kde](https://github.com/PapirusDevelopmentTeam/arc-kde)
* [https://store.kde.org/u/x-varlesh-x](https://store.kde.org/u/x-varlesh-x)
* [Arc Light KDE](https://store.kde.org/p/1815459)
* [Arc Dark KDE](https://store.kde.org/p/1167638)
* GitHub / [varlesh](https://github.com/varlesh)


## Docs

| Docs |
| --- |
| [Config File Path](helper/doc/config.md) |


## Howto

### prepare

to install [live-build](https://packages.debian.org/sid/live-build)

``` sh
make prepare
```


### build

to build iso

``` sh
make build
```


### run_iso

to test iso

```
make run_iso
```

### clean

to clean dir: [tmp]

``` sh
make clean
```


### make-profile

``` sh
THE_DEFAULT_RUN=make-profile make build
```

``` sh
THE_DEFAULT_RUN=make-profile make main-lxqt
```


## Reference


