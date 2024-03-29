<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Kiwix per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/kiwix.svg)](https://dash.yunohost.org/appci/app/kiwix) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![Installa Kiwix con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Kiwix su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Versione pubblicata:** 3.6.0~ynh1

**Prova:** <http://library.kiwix.org/>

## Screenshot

![Screenshot di Kiwix](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://www.kiwix.org/>
- Documentazione ufficiale per gli amministratori: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Repository upstream del codice dell’app: <https://github.com/kiwix/kiwix-tools>
- Store di YunoHost: <https://apps.yunohost.org/app/kiwix>
- Segnala un problema: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
o
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
