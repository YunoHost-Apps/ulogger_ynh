<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# ulogger pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/ulogger)](https://ci-apps.yunohost.org/ci/apps/ulogger/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/ulogger)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/ulogger)

[![Installer ulogger avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ulogger)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer ulogger rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

μlogger is a web application for real-time collection of geolocation data, tracks viewing and management. 

Together with a dedicated [μlogger mobile client](https://github.com/bfabiszewski/ulogger-android) it may be used as a complete self hosted server–client solution for logging and monitoring users' geolocation.


**Version incluse :** 1.2~ynh1

## Captures d’écran

![Capture d’écran de ulogger](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/bfabiszewski/ulogger-server>
- YunoHost Store : <https://apps.yunohost.org/app/ulogger>
- Signaler un bug : <https://github.com/YunoHost-Apps/ulogger_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ulogger -u https://github.com/YunoHost-Apps/ulogger_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
