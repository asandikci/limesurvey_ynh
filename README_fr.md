<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# LimeSurvey pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/limesurvey.svg)](https://dash.yunohost.org/appci/app/limesurvey) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/limesurvey.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/limesurvey.maintain.svg)

[![Installer LimeSurvey avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=limesurvey)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d’installer LimeSurvey rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Outil de création et diffusion de sondage


**Version incluse :** 5.6.8+230227~ynh1

## Captures d’écran

![Capture d’écran de LimeSurvey](./doc/screenshots/create_html_statistic_screen.png)

## Avertissements / informations importantes

### Caractéristiques spécifiques de YunoHost

* En mode privé, seuls les membres autorisés de YunoHost peuvent créer des sondages, en mode public, il est possible de créer des comptes pour les personnes n'ayant pas de compte YunoHost.
* SSO et LDAP sont configurés.
* Login sécurisé par fail2ban

## Documentations et ressources

* Site officiel de l’app : <https://www.limesurvey.org>
* Documentation officielle utilisateur : <https://help.limesurvey.org>
* Documentation officielle de l’admin : <https://manual.limesurvey.org/LimeSurvey_Manual/fr>
* Dépôt de code officiel de l’app : <https://github.com/LimeSurvey/LimeSurvey>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_limesurvey>
* Signaler un bug : <https://github.com/YunoHost-Apps/limesurvey_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing --debug
ou
sudo yunohost app upgrade limesurvey -u https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>