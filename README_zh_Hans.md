<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 KiwiIRC

[![集成程度](https://dash.yunohost.org/integration/kiwiirc.svg)](https://dash.yunohost.org/appci/app/kiwiirc) ![工作状态](https://ci-apps.yunohost.org/ci/badges/kiwiirc.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/kiwiirc.maintain.svg)

[![使用 YunoHost 安装 KiwiIRC](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwiirc)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 KiwiIRC。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A versatile web based messenger using IRC

### Features:

- For single networks, bouncer hosts, or a personal generic IRC client that remembers your networks
- Works out of the box with a default IRC network - or use your own
- Single or multiple IRC network connections
- Light and dark modes
- Desktop notifications
- Extremely versatile via a single JSON config file at runtime


**分发版本：** 1.7.1~ynh1

**演示：** <https://kiwiirc.com/nextclient>

## 截图

![KiwiIRC 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://kiwiirc.com/>
- 官方管理文档： <https://github.com/kiwiirc/kiwiirc/wiki>
- 上游应用代码库： <https://github.com/kiwiirc/kiwiirc>
- YunoHost 商店： <https://apps.yunohost.org/app/kiwiirc>
- 报告 bug： <https://github.com/YunoHost-Apps/kiwiirc_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing --debug
或
sudo yunohost app upgrade kiwiirc -u https://github.com/YunoHost-Apps/kiwiirc_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
