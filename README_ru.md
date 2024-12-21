<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Uptime Kuma для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/uptime-kuma)](https://ci-apps.yunohost.org/ci/apps/uptime-kuma/)
![Состояние работы](https://apps.yunohost.org/badge/state/uptime-kuma)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/uptime-kuma)

[![Установите Uptime Kuma с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Uptime Kuma быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Uptime Kuma is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP)...
- 20 second intervals
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Поставляемая версия:** 2.0.0~ynh1

**Демо-версия:** <https://demo.uptime.kuma.pet>

## Снимки экрана

![Снимок экрана Uptime Kuma](./doc/screenshots/example.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://uptime.kuma.pet/>
- Официальная документация пользователя: <https://github.com/louislam/uptime-kuma/wiki>
- Репозиторий кода главной ветки приложения: <https://github.com/louislam/uptime-kuma>
- Магазин YunoHost: <https://apps.yunohost.org/app/uptime-kuma>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
или
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
