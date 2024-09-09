<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Kiwix untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/kiwix.svg)](https://ci-apps.yunohost.org/ci/apps/kiwix/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![Pasang Kiwix dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Kiwix secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Versi terkirim:** 3.6.0~ynh3

**Demo:** <http://library.kiwix.org/>

## Tangkapan Layar

![Tangkapan Layar pada Kiwix](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.kiwix.org/>
- Dokumentasi admin resmi: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Depot kode aplikasi hulu: <https://github.com/kiwix/kiwix-tools>
- Gudang YunoHost: <https://apps.yunohost.org/app/kiwix>
- Laporkan bug: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
atau
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
