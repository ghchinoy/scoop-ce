# Scoop Bucket for Cloud Elements Windows Utilities

This repository contains a custom bucket for [scoop.sh] to install Cloud Elements 
(unofficial) software.


To use this, after installing scoop, open PowerShell and type:

```
scoop bucket add cloudelements https://github.com/ghchinoy/scoop-ce
```

Test that the bucket is present:

```
> scoop bucket list
cloudelements
```

The following tools are referenced:

* [cectl](https://github.com/ghchinoy/rwctl) - a CLI for the Cloud Elements platform
