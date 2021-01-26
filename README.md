# μlogger for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ulogger.svg)](https://dash.yunohost.org/appci/app/ulogger) ![](https://ci-apps.yunohost.org/ci/badges/ulogger.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ulogger.maintain.svg)  
[![Install μlogger with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ulogger)

> *This package allows you to install μlogger quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
This is a web application for real-time collection of geolocation data, tracks viewing and management. Together with a dedicated [μlogger mobile client](https://github.com/bfabiszewski/ulogger-android) it may be used as a complete self hosted server–client solution for logging and monitoring users' geolocation.

**Version:** 1.0

## Demo
* [Official demo](http://ulogger.fabiszewski.net/) (login: demo, password: demo)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

* Are LDAP and HTTP auth supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/ulogger%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/ulogger/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/ulogger%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/ulogger/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/ulogger_ynh/issues
 * Upstream app repository: https://github.com/bfabiszewski/ulogger-server
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
or
sudo yunohost app upgrade ulogger -u https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
```
