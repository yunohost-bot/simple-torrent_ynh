<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Simple Torrent YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simple-torrent) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)

[![Instalatu Simple Torrent YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Simple Torrent YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 1.3.9~ynh8

## Pantaila-argazkiak

![Simple Torrent(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://github.com/boypt/simple-torrent/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/boypt/simple-torrent>
- YunoHost Denda: <https://apps.yunohost.org/app/simple-torrent>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/simple-torrent_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
edo
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
