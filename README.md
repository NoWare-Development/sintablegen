# SinTableGen

__SinTableGen__ is a simple utility to generate sin tables.

Default size of the generated sin table is 65536.
But you also can provide your size of sin table through arguments.
```
$ sintablegen 80000
```

Output of __SinTableGen__ will be in file `sintable.h`.

You can also see an example output in [sintable.h](https://github.com/NoWare-Development/sintable.h) repository.

## Manual build
__Tools__: [meson](https://mesonbuild.com/), [ninja](https://ninja-build.org/)

```
$ git clone https://github.com/NoWare-Development/sintablegen.git
$ cd sintablegen
$ meson setup build
$ ninja -C build
```
