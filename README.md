<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Lidarr for YunoHost

[![Integration level](https://dash.yunohost.org/integration/lidarr.svg)](https://dash.yunohost.org/appci/app/lidarr) ![](https://ci-apps.yunohost.org/ci/badges/lidarr.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/lidarr.maintain.svg)  
[![Install Lidarr with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=lidarr)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Lidarr quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A music collection manager for Usenet and BitTorrent users.

**Shipped version:** 0.8.1.2135~ynh1



## Screenshots

![](./doc/screenshots/screenshot.jpg)

## Disclaimers / important information

* Supported architectures are `arm`, `arm64`, and `amd64`
* Access control is done with YunoHost's permissions system.
  * API (`domain.tld/path/api`) can be accessed by visitors to allow control by remote clients.
* The app uses YunoHost's multimedia directories, hence it has write access to users' and shared directories in `/home/yunohost.multimedia`. After installation, you can choose these directories to store your media.

## Documentation and resources

* Official app website: https://lidarr.audio
* Official admin documentation: https://wiki.servarr.com/Lidarr
* Upstream app code repository: https://github.com/Lidarr/Lidarr
* YunoHost documentation for this app: https://yunohost.org/app_lidarr
* Report a bug: https://github.com/YunoHost-Apps/lidarr_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/lidarr_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/lidarr_ynh/tree/testing --debug
or
sudo yunohost app upgrade lidarr -u https://github.com/YunoHost-Apps/lidarr_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps