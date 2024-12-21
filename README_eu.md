<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Uptime Kuma YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/uptime-kuma)](https://ci-apps.yunohost.org/ci/apps/uptime-kuma/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/uptime-kuma)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/uptime-kuma)

[![Instalatu Uptime Kuma YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Uptime Kuma YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Uptime Kuma is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP)...
- 20 second intervals
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Paketatutako bertsioa:** 2.0.0~ynh1

**Demoa:** <https://demo.uptime.kuma.pet>

## Pantaila-argazkiak

![Uptime Kuma(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://uptime.kuma.pet/>
- Erabiltzaileen dokumentazio ofiziala: <https://github.com/louislam/uptime-kuma/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/louislam/uptime-kuma>
- YunoHost Denda: <https://apps.yunohost.org/app/uptime-kuma>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
edo
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
