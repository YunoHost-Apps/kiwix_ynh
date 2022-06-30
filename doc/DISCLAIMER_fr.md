### Comment ajouter des fichiers ZIM ?

- Téléchargez un ou plusieurs fichiers ZIM, par ex. [https://download.kiwix.org/zim/](https://download.kiwix.org/zim/)
- Mettez les fichiers ZIM dans `/home/yunohost.app/kiwix/`
- Ajoutez-les à la bibliothèque avec la commande suivante :
```
/var/www/kiwix/kiwix-manage /home/yunohost.app/kiwix/library.xml add /home/yunohost.app/kiwix/*.zim
```

- Redémarrez le service :

`yunohost service restart kiwix`
