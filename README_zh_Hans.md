<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Uptime Kuma

[![集成程度](https://apps.yunohost.org/badge/integration/uptime-kuma)](https://ci-apps.yunohost.org/ci/apps/uptime-kuma/)
![工作状态](https://apps.yunohost.org/badge/state/uptime-kuma)
![维护状态](https://apps.yunohost.org/badge/maintained/uptime-kuma)

[![使用 YunoHost 安装 Uptime Kuma](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Uptime Kuma。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Uptime Kuma is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP)...
- 20 second intervals
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**分发版本：** 2.0.0~ynh1

**演示：** <https://demo.uptime.kuma.pet>

## 截图

![Uptime Kuma 的截图](./doc/screenshots/example.jpg)

## 文档与资源

- 官方应用网站： <https://uptime.kuma.pet/>
- 官方用户文档： <https://github.com/louislam/uptime-kuma/wiki>
- 上游应用代码库： <https://github.com/louislam/uptime-kuma>
- YunoHost 商店： <https://apps.yunohost.org/app/uptime-kuma>
- 报告 bug： <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
或
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
