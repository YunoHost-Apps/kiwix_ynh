<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Kiwix pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/kiwix)](https://ci-apps.yunohost.org/ci/apps/kiwix/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/kiwix)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/kiwix)

[![Installer Kiwix avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Kiwix rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Kiwix est un lecteur hors-ligne pour contenus web qui permet en particulier d’accéder à Wikipédia sans connexion à Internet.

### Fonctionnalités
- Un moteur de recherche de tout texte
- Suggestions de recherche
- Compatible avec la majorité des navigateurs internet
- Disponible par ligne de commande exécutables
- Embedded in Kiwix UI
- Capable de traiter un fichier ZIM ou des fichiers de bibliothèque XML


**Version incluse :** 3.6.0~ynh3

**Démo :** <http://library.kiwix.org/>

## Captures d’écran

![Capture d’écran de Kiwix](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.kiwix.org/>
- Documentation officielle de l’admin : <https://wiki.kiwix.org/wiki/Kiwix-serve/>
- Dépôt de code officiel de l’app : <https://github.com/kiwix/kiwix-tools>
- YunoHost Store : <https://apps.yunohost.org/app/kiwix>
- Signaler un bug : <https://github.com/YunoHost-Apps/kiwix_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
ou
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
