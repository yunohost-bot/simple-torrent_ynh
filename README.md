<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Simple Torrent for YunoHost

[![Integration level](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simple-torrent) ![Working status](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)

[![Install Simple Torrent with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Simple Torrent quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

SimpleTorrent is a a self-hosted remote torrent client, written in Go (golang). Started torrents remotely, download sets of files on the local disk of the server, which are then retrievable or streamable via HTTP.

### Features

- Individual file download control (1.1.3+)
- Run external program on tasks completion
- Stops task when seeding ratio reached
- Download/Upload speed limiter
- Detailed transfer stats in web UI.
- Torrent Watcher
- Extra trackers from external source
- Protocol Handler to magnet
- Magnet RSS subscribing supported


**Shipped version:** 1.3.9~ynh8

## Screenshots

![Screenshot of Simple Torrent](./doc/screenshots/screenshot.png)

## :red_circle: Antifeatures

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentation and resources

* Official admin documentation: <https://github.com/boypt/simple-torrent/wiki>
* Upstream app code repository: <https://github.com/boypt/simple-torrent>
* YunoHost Store: <https://apps.yunohost.org/app/simple-torrent>
* Report a bug: <https://github.com/YunoHost-Apps/simple-torrent_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
or
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
