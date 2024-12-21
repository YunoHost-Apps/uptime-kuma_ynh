<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Uptime Kuma untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/uptime-kuma)](https://ci-apps.yunohost.org/ci/apps/uptime-kuma/)
![Status kerja](https://apps.yunohost.org/badge/state/uptime-kuma)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/uptime-kuma)

[![Pasang Uptime Kuma dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Uptime Kuma secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Uptime Kuma is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP)...
- 20 second intervals
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Versi terkirim:** 2.0.0~ynh1

**Demo:** <https://demo.uptime.kuma.pet>

## Tangkapan Layar

![Tangkapan Layar pada Uptime Kuma](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://uptime.kuma.pet/>
- Dokumentasi pengguna resmi: <https://github.com/louislam/uptime-kuma/wiki>
- Depot kode aplikasi hulu: <https://github.com/louislam/uptime-kuma>
- Gudang YunoHost: <https://apps.yunohost.org/app/uptime-kuma>
- Laporkan bug: <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
atau
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
