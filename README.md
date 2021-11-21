# nb-franklin

Export [nb] notes to markdown pages compatible with [Franklin].

**Installation**
```
nb plugin install https://github.com/fredrikekre/nb-franklin/blob/master/franklin.nb-plugin
```

**Usage**
Export `nb` note given by `<selector>` to the file `destination`:
```
nb franklin <selector> destination
```
If destination is empty, or `-`, write to standard out.

[nb]: https://github.com/xwmx/nb
[Franklin]: https://github.com/tlienart/Franklin.jl
