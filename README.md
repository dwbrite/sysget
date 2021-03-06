# sysget

[![Build Status](https://travis-ci.org/emilengler/sysget.svg?branch=master)](https://travis-ci.org/emilengler/sysget)
### A front-end for every package manager<br>
sysget is a bridge that lets you use one syntax to every package manager on every unix-based operating system.<br>
You probably all know the problem when you are on a new distro and don't know anything about the package manager. With sysget you just need to remember one syntax for every package manager.<br>
The syntax is mostly same with apt-get so it should be easy to use. <br>
### Supported package managers:
* apt-get
* xbps
* dnf
* yum
* zypper
* eopkg
* pacman
* emerge
* pkg
* chromebrew
* homebrew
* nix
* snap
* npm

### Features
* search for packages
* install packages
* remove packages
* remove orphans
* clear package manager cache
* update database
* upgrade system
* upgrade single package

### How to install
```make && sudo make install```<br>
No dependencies needed

### Example
To install a package
```
sysget install <package name>
```
To remove a package
```
sysget remove <package name>
```
To update the database
```
sysget update
```
To upgrade the system
```
sysget upgrade
```
To upgrade a specific package
```
sysget upgrade <package name>
```
To remove orphans
```
sysget autoremove
```
To clean the cache of the package manager
```
sysget clean
```
###### Credits
[TermGet](https://github.com/termget/termget)
