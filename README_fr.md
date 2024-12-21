<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Uptime Kuma pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/uptime-kuma)](https://ci-apps.yunohost.org/ci/apps/uptime-kuma/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/uptime-kuma)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/uptime-kuma)

[![Installer Uptime Kuma avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Uptime Kuma rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Uptime Kuma est un outil de surveillance auto-hébergé comme « Uptime Robot ».

### Caractéristiques

- Surveillance de la disponibilité pour HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, E-mail (SMTP)...
- intervalles de 20 secondes
- Multi langues
- Page d'état simple
- Graphique Ping
- Informations sur le certificat

**Version incluse :** 2.0.0~ynh1

**Démo :** <https://demo.uptime.kuma.pet>

## Captures d’écran

![Capture d’écran de Uptime Kuma](./doc/screenshots/example.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://uptime.kuma.pet/>
- Documentation officielle utilisateur : <https://github.com/louislam/uptime-kuma/wiki>
- Dépôt de code officiel de l’app : <https://github.com/louislam/uptime-kuma>
- YunoHost Store : <https://apps.yunohost.org/app/uptime-kuma>
- Signaler un bug : <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
ou
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
