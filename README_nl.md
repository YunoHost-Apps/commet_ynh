<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Commet voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/commet.svg)](https://ci-apps.yunohost.org/ci/apps/commet/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/commet.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/commet.maintain.svg)

[![Commet met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commet)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Commet snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Commet is a client for Matrix that aims to provide a feature-rich experience while maintaining a simple interface. The goal is to create a secure and privacy-friendly app without compromising the features you expect from a modern chat client.

### Features

- End-to-end encryption
- Custom emoji + stickers
- GIF search
- Multiple accounts
- Spaces
- Emoji verification and cross-signature
- Push notifications
- URL preview


**Geleverde versie:** 0.3.0~ynh1

**Demo:** <https://app.commet.chat/>

## Schermafdrukken

![Schermafdrukken van Commet](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://commet.chat/>
- Upstream app codedepot: <https://github.com/commetchat/commet>
- YunoHost-store: <https://apps.yunohost.org/app/commet>
- Meld een bug: <https://github.com/YunoHost-Apps/commet_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/commet_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
of
sudo yunohost app upgrade commet -u https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
