<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Simple Torrent

[![集成程度](https://dash.yunohost.org/integration/simple-torrent.svg)](https://dash.yunohost.org/appci/app/simple-torrent) ![工作状态](https://ci-apps.yunohost.org/ci/badges/simple-torrent.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/simple-torrent.maintain.svg)

[![使用 YunoHost 安装 Simple Torrent](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-torrent)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Simple Torrent。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 1.3.9~ynh8

## 截图

![Simple Torrent 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方管理文档： <https://github.com/boypt/simple-torrent/wiki>
- 上游应用代码库： <https://github.com/boypt/simple-torrent>
- YunoHost 商店： <https://apps.yunohost.org/app/simple-torrent>
- 报告 bug： <https://github.com/YunoHost-Apps/simple-torrent_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
或
sudo yunohost app upgrade simple-torrent -u https://github.com/YunoHost-Apps/simple-torrent_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
