# sysdetect

A library to detect the operating system and architecture without forking a
subprocess.

We are not going for an exhaustive list of every historical system here, but
we're aiming to cover at least every platform where LuaRocks is known to run.
If your system is not detected, patches are welcome!

## Installing

Install with:

```
luarocks install sysdetect
```

## Building

This library is written in [Teal](https://github.com/teal-language).
Install [Cyan](https://github.com/teal-language/cyan) with `luarocks install cyan` then
run:

```
cyan build
```

Or you can use LuaRocks to run Cyan to build and install the package in one go
using `luarocks make`.

## Testing

The test suite uses Busted. You can run it with:

```
luarocks test
```
