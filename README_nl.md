<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Kiwix voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/kiwix.svg)](https://ci-apps.yunohost.org/ci/apps/kiwix/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![Kiwix met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Kiwix snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Geleverde versie:** 3.6.0~ynh3

**Demo:** <http://library.kiwix.org/>

## Schermafdrukken

![Schermafdrukken van Kiwix](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://www.kiwix.org/>
- Officiele beheerdersdocumentatie: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Upstream app codedepot: <https://github.com/kiwix/kiwix-tools>
- YunoHost-store: <https://apps.yunohost.org/app/kiwix>
- Meld een bug: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
of
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
