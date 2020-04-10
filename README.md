# build-supercollider

A _dead simple_ script that installs (build) dependencies, clones [Supercollider](https://github.com/supercollider/supercollider/), builds it, and finally will install it.

## Current version:

> 3.11


## How to?

```bash
$ git clone https://github.com/lvm/build-supercollider
$ cd build-supercollider
$ sh build-supercollider.sh
$ sh build-sc3-plugins.sh
```

That's all.  
Keep in mind this script works on Debian-derivates distributions (such as Ubuntu, Mint, etc). Sorry Windows, OS X, and other GNU/linux distros.

See [README-deb.md](README-deb.md) for thoughts on making .deb packages.
