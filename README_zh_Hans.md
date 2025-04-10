<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 ulogger

[![集成程度](https://apps.yunohost.org/badge/integration/ulogger)](https://ci-apps.yunohost.org/ci/apps/ulogger/)
![工作状态](https://apps.yunohost.org/badge/state/ulogger)
![维护状态](https://apps.yunohost.org/badge/maintained/ulogger)

[![使用 YunoHost 安装 ulogger](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ulogger)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 ulogger。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

μlogger is a web application for real-time collection of geolocation data, tracks viewing and management. 

Together with a dedicated [μlogger mobile client](https://github.com/bfabiszewski/ulogger-android) it may be used as a complete self hosted server–client solution for logging and monitoring users' geolocation.


**分发版本：** 1.2~ynh1

## 截图

![ulogger 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 上游应用代码库： <https://github.com/bfabiszewski/ulogger-server>
- YunoHost 商店： <https://apps.yunohost.org/app/ulogger>
- 报告 bug： <https://github.com/YunoHost-Apps/ulogger_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
或
sudo yunohost app upgrade ulogger -u https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
