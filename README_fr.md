<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Commet pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/commet.svg)](https://ci-apps.yunohost.org/ci/apps/commet/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/commet.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/commet.maintain.svg)

[![Installer Commet avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commet)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Commet rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Commet est un client pour Matrix qui vise à fournir une expérience riche en fonctionnalités tout en conservant une interface simple. L'objectif est de créer une application sécurisée et respectueuse de la vie privée sans compromettre les fonctionnalités que vous attendez d'un client de chat moderne.

### Fonctionnalités

- Cryptage de bout en bout
- Emoji personnalisé + autocollants
- Recherche GIF
- Comptes multiples
- Espaces
- Vérification des emoji et signature croisée
- Notifications push
- Aperçu de l'URL


**Version incluse :** 0.2.1~ynh1

**Démo :** <https://app.commet.chat/>

## Captures d’écran

![Capture d’écran de Commet](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://commet.chat/>
- Documentation officielle utilisateur : <https://yunohost.org/apps>
- Documentation officielle de l’admin : <https://yunohost.org/packaging_apps>
- Dépôt de code officiel de l’app : <https://github.com/commetchat/commet>
- YunoHost Store : <https://apps.yunohost.org/app/commet>
- Signaler un bug : <https://github.com/YunoHost-Apps/commet_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/commet_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
ou
sudo yunohost app upgrade commet -u https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
