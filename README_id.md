<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Commet untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/commet)](https://ci-apps.yunohost.org/ci/apps/commet/)
![Status kerja](https://apps.yunohost.org/badge/state/commet)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/commet)

[![Pasang Commet dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=commet)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Commet secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 0.3.0~ynh1

**Demo:** <https://app.commet.chat/>

## Tangkapan Layar

![Tangkapan Layar pada Commet](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://commet.chat/>
- Depot kode aplikasi hulu: <https://github.com/commetchat/commet>
- Gudang YunoHost: <https://apps.yunohost.org/app/commet>
- Laporkan bug: <https://github.com/YunoHost-Apps/commet_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/commet_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
atau
sudo yunohost app upgrade commet -u https://github.com/YunoHost-Apps/commet_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
