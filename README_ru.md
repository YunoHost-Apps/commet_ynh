<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Commet для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/commet.svg)](https://ci-apps.yunohost.org/ci/apps/commet/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/commet.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/commet.maintain.svg)

[![Установите Commet с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commet)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Commet быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 0.2.1~ynh1

**Демо-версия:** <https://app.commet.chat/>

## Снимки экрана

![Снимок экрана Commet](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://commet.chat/>
- Репозиторий кода главной ветки приложения: <https://github.com/commetchat/commet>
- Магазин YunoHost: <https://apps.yunohost.org/app/commet>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/commet_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/commet_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
или
sudo yunohost app upgrade commet -u https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
