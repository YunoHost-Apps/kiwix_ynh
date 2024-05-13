<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Kiwix YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/kiwix.svg)](https://dash.yunohost.org/appci/app/kiwix) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![Instalatu Kiwix YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Kiwix YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Paketatutako bertsioa:** 3.6.0~ynh2

**Demoa:** <http://library.kiwix.org/>

## Pantaila-argazkiak

![Kiwix(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.kiwix.org/>
- Administratzaileen dokumentazio ofiziala: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/kiwix/kiwix-tools>
- YunoHost Denda: <https://apps.yunohost.org/app/kiwix>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
edo
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
