<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Simple Torrent para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simple-torrent) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)

[![Instalar Simple Torrent con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarSimple Torrent rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 1.3.9~ynh8

## Capturas

![Captura de Simple Torrent](./doc/screenshots/screenshot.png)

## :red_circle: funcionalidades no deseadas

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Documentación administrador oficial: <https://github.com/boypt/simple-torrent/wiki>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/boypt/simple-torrent>
- Catálogo YunoHost: <https://apps.yunohost.org/app/simple-torrent>
- Reportar un error: <https://github.com/YunoHost-Apps/simple-torrent_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
o
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
