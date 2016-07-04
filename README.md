Blackbird
=========
Desktop Suite for Xfce
----------------------

Copyright 2012 Simon Steinbeiß and Satyajit Sahoo

Blackbird is dual-licensed as GPLv2 or later and CC-BY-SA 3.0 or later.


The Blackbird desktop suite includes:
* GTK2 theme
* GTK3 theme (WIP)
* Xfwm4 theme
* Metacity theme

### Install without admin privileges

```
./autogen.sh --prefix=$HOME/.local
make install
```

### Install for all users

```
./autogen.sh
sudo make install
```
