<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Uptime Kuma per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/uptime-kuma.svg)](https://dash.yunohost.org/appci/app/uptime-kuma) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.maintain.svg)

[![Installa Uptime Kuma con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Uptime Kuma su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Uptime Kuma is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP)...
- 20 second intervals
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Versione pubblicata:** 1.23.11~ynh1

**Prova:** <https://demo.uptime.kuma.pet>

## Screenshot

![Screenshot di Uptime Kuma](./doc/screenshots/example.jpg)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://uptime.kuma.pet/>
- Documentazione ufficiale per gli utenti: <https://github.com/louislam/uptime-kuma/wiki>
- Repository upstream del codice dell’app: <https://github.com/louislam/uptime-kuma>
- Store di YunoHost: <https://apps.yunohost.org/app/uptime-kuma>
- Segnala un problema: <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
o
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
