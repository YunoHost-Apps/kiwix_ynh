<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Kiwix para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/kiwix.svg)](https://ci-apps.yunohost.org/ci/apps/kiwix/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)

[![Instalar Kiwix con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarKiwix rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Kiwix is an offline reader for online content like Wikipedia, Project Gutenberg, or TED Talks. It makes knowledge available to people with no or limited internet access. The software as well as the content is free to use for anyone.

### Features

- Full text search engine
- Search suggestions
- Compatible with almost all browsers
- Available as command line executable
- Embedded in Kiwix UI
- Able to deal with one ZIM file or XML library files


**Versión actual:** 3.6.0~ynh3

**Demo:** <http://library.kiwix.org/>

## Capturas

![Captura de Kiwix](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://www.kiwix.org/>
- Documentación administrador oficial: <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/kiwix/kiwix-tools>
- Catálogo YunoHost: <https://apps.yunohost.org/app/kiwix>
- Reportar un error: <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
o
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
