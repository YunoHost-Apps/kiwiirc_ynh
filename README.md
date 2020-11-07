# KiwiIRC for YunoHost

[![Integration level](https://dash.yunohost.org/integration/kiwiirc.svg)](https://dash.yunohost.org/appci/app/kiwiirc) ![](https://ci-apps.yunohost.org/ci/badges/kiwiirc.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/kiwiirc.maintain.svg)  
[![Install KiwiIRC with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=kiwiirc)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install KiwiIRC quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
KiwiIRC is a versatile web based messenger using IRC.

**Shipped version:** 1.5.0

## Screenshots

![](https://kiwiirc.com/img/screenshot.png)

## Demo

* [Official demo]()

## Configuration


## Documentation

 * Official documentation: https://github.com/kiwiirc/kiwiirc/wiki
 * YunoHost documentation: 

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/kiwiirc%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/kiwiirc/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/kiwiirc%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/kiwiirc/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/kiwiirc_ynh/issues
 * Upstream app repository: https://github.com/kiwiirc/kiwiirc
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing --debug
or
sudo yunohost app upgrade kiwiirc -u https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing --debug
```
