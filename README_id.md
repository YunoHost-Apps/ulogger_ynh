<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# ulogger untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/ulogger)](https://ci-apps.yunohost.org/ci/apps/ulogger/)
![Status kerja](https://apps.yunohost.org/badge/state/ulogger)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/ulogger)

[![Pasang ulogger dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ulogger)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang ulogger secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

μlogger is a web application for real-time collection of geolocation data, tracks viewing and management. 

Together with a dedicated [μlogger mobile client](https://github.com/bfabiszewski/ulogger-android) it may be used as a complete self hosted server–client solution for logging and monitoring users' geolocation.


**Versi terkirim:** 1.2~ynh1

## Tangkapan Layar

![Tangkapan Layar pada ulogger](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/bfabiszewski/ulogger-server>
- Gudang YunoHost: <https://apps.yunohost.org/app/ulogger>
- Laporkan bug: <https://github.com/YunoHost-Apps/ulogger_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
atau
sudo yunohost app upgrade ulogger -u https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
