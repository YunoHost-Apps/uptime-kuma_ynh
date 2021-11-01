# Uptime Kuma pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/uptime-kuma.svg)](https://dash.yunohost.org/appci/app/uptime-kuma) ![](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.maintain.svg)  
[![Installer Uptime Kuma avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Uptime Kuma rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

It is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Fancy, Reactive, Fast UI/UX.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP), and 70+ notification services, click here for the full list.
- 20 second intervals.
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Version incluse :** 1.0~ynh1

**Démo :** https://demo.uptime.kuma.pet

## Captures d'écran

![](./doc/screenshots/example.jpg)

## Avertissements / informations importantes

- Not working yet
- Requires a full dedicated domain
- Uses N to install specific nodejs version
- ARM architecture not supported
- No upgrade script in this package
- does not properly use port reserved by yunohost
- needs post-install
<!-- * Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...


- Other infos that people should be aware of, such as:
  - any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
  - how to configure / administrate the application if it ain't obvious
  - upgrade process / specificities / things to be aware of ?
  - security considerations ? -->

## Documentations et ressources

* Site officiel de l'app : https://uptime.kuma.pet/
* Documentation officielle utilisateur : https://github.com/louislam/uptime-kuma/wiki
* Documentation officielle de l'admin : https://github.com/louislam/uptime-kuma/wiki
* Dépôt de code officiel de l'app : https://github.com/louislam/uptime-kuma/
* Documentation YunoHost pour cette app : https://yunohost.org/app_uptime-kuma
* Signaler un bug : https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
ou
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps