<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Uptime Kuma voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/uptime-kuma)](https://ci-apps.yunohost.org/ci/apps/uptime-kuma/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/uptime-kuma)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/uptime-kuma)

[![Uptime Kuma met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Uptime Kuma snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Uptime Kuma is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP)...
- 20 second intervals
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Geleverde versie:** 2.0.0~ynh1

**Demo:** <https://demo.uptime.kuma.pet>

## Schermafdrukken

![Schermafdrukken van Uptime Kuma](./doc/screenshots/example.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://uptime.kuma.pet/>
- Officiele gebruikersdocumentatie: <https://github.com/louislam/uptime-kuma/wiki>
- Upstream app codedepot: <https://github.com/louislam/uptime-kuma>
- YunoHost-store: <https://apps.yunohost.org/app/uptime-kuma>
- Meld een bug: <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
of
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
