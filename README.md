## dmenu

[dmenu](https://github.com/minos-org/dmenu/) s a dynamic menu for X, it manages large numbers of user-defined menu items efficiently. This is a custom + freeze version, refer to [suckless](http://tools.suckless.org/dmenu/) for the original one.

<p align="center">
<img src="https://raw.githubusercontent.com/minos-org/dmenu/master/dmenu.jpg" alt="dmenu"/>
</p>

## Quick start

### On Ubuntu (only LTS releases)

1. Set up the minos archive:

   ```
   $ sudo add-apt-repository ppa:minos-archive/main
   ```
   
2. Install:

   ```   
   $ sudo apt-get update && sudo apt-get install dmenu
   ```

3. Enjoy ☺!

### On other Linux distributions

1. Edit config.mk to match your local setup

2. Type `make`

3. Type `sudo make install`

## Differences

* XFT support by default
* dmenu_run less
