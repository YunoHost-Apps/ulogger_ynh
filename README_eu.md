<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# ulogger YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/ulogger.svg)](https://dash.yunohost.org/appci/app/ulogger) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/ulogger.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/ulogger.maintain.svg)

[![Instalatu ulogger YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ulogger)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek ulogger YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

μlogger is a web application for real-time collection of geolocation data, tracks viewing and management. 

Together with a dedicated [μlogger mobile client](https://github.com/bfabiszewski/ulogger-android) it may be used as a complete self hosted server–client solution for logging and monitoring users' geolocation.


**Paketatutako bertsioa:** 1.1~ynh2

## Pantaila-argazkiak

![ulogger(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/bfabiszewski/ulogger-server>
- YunoHost Denda: <https://apps.yunohost.org/app/ulogger>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/ulogger_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
edo
sudo yunohost app upgrade ulogger -u https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
