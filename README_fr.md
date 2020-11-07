# KiwiIRC pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/kiwiirc.svg)](https://dash.yunohost.org/appci/app/kiwiirc) ![](https://ci-apps.yunohost.org/ci/badges/kiwiirc.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/kiwiirc.maintain.svg)  
[![Installer kiwiIRC avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=kiwiirc)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer kiwiIRC rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
KiwiIRC est un messager Web polyvalent utilisant IRC.

**Version incluse :** 1.5.0

## Captures d'écran

![](https://kiwiirc.com/img/screenshot.png)

## Démo

* [Démo officielle]()

## Configuration

## Documentation

 * Documentation officielle : https://github.com/kiwiirc/kiwiirc/wiki
 * Documentation YunoHost : 

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/kiwiirc%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/kiwiirc/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/kiwiirc%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/kiwiirc/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/kiwiirc_ynh/issues
 * Dépôt de l'application principale : https://github.com/kiwiirc/kiwiirc
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing --debug
ou
sudo yunohost app upgrade kiwiirc -u https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing --debug
```
