### Comment ajouter des fichiers ZIM ?

#### Ajouter un fichier ZIM via son URL
- Sélectionnez l'onglet "Upload content" qui se trouve ci-dessus.

#### Ajouter un fichier ZIM à la main
- Téléchargez un ou plusieurs fichiers ZIM, par ex. [https://download.kiwix.org/zim/](https://download.kiwix.org/zim/)
- Mettez les fichiers ZIM dans `__DATA_DIR__/`
- Ajoutez-les à la bibliothèque avec la commande suivante :

```
sudo yunohost app shell __APP__
./kiwix-manage __DATA_DIR__/library.xml add __DATA_DIR__/*.zim
```

- Redémarrez le service :

`yunohost service restart kiwix`
