<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Kiwix dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/kiwix)](https://ci-apps.yunohost.org/ci/apps/kiwix/)
![Status działania](https://apps.yunohost.org/badge/state/kiwix)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/kiwix)

[![Zainstaluj Kiwix z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Kiwix na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Dostarczona wersja:** 3.6.0~ynh3

**Demo:** <http://library.kiwix.org/>

## Zrzuty ekranu

![Zrzut ekranu z Kiwix](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://www.kiwix.org/>
- Oficjalna dokumentacja dla administratora: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Repozytorium z kodem źródłowym: <https://github.com/kiwix/kiwix-tools>
- Sklep YunoHost: <https://apps.yunohost.org/app/kiwix>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
lub
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
