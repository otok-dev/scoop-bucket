# Scoop bucket for otok

[otok](https://github.com/otok-dev/otok) is a dependency manager that builds native libraries from source on
your machine and hands them to your build.

## Install

With [Scoop](https://scoop.sh):

```powershell
scoop bucket add otok https://github.com/otok-dev/scoop-bucket
scoop install otok
```

otok builds with Visual Studio's C++ tools and git of your machine (`scoop install git`); the other tools recipes
need (CMake, Ninja, Python, MSYS2's make, ...) are built or fetched by their own recipes.

## Update

```powershell
scoop update
scoop update otok
```
