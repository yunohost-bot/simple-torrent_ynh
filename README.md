<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Simple Torrent for YunoHost

[![Integration level](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simple-torrent) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)  
[![Install Simple Torrent with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Simple Torrent quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Self-hosted remote torrent client

**Shipped version:** 1.2.23~ynh3



## Screenshots

![](./doc/screenshots/64239393-bdbb6480-cf32-11e9-9269-d8d10e7c0dc7.png)
![](./doc/screenshots/.DS_Store)

## Disclaimers / important information

## Configuration

Most of the items can be edited in Web-UI on the fly in the config board.

You can also configure Simple Torrent by editing this file `/var/www/simple-torrent/config.json` using the [documentation](https://github.com/boypt/simple-torrent/wiki/Config-File).

## Limitations

- This app cannot be installed on a 32-bit ARM machine.

## Documentation and resources

* Official app website: https://github.com/boypt/simple-torrent
* Official admin documentation: https://github.com/boypt/simple-torrent/wiki
* Upstream app code repository: https://github.com/boypt/simple-torrent
* YunoHost documentation for this app: https://yunohost.org/app_simple-torrent
* Report a bug: https://github.com/YunoHost-Apps/simple-torrent_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
or
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps